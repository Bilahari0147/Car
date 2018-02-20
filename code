#include <stdio.h>
#include <iostream>
#include "GL/freeglut.h"
#include "GL/gl.h"

using namespace std;
int translate =0;
int rotate = 0;
int view =0;
void init()
{
glClearColor(1.0,1.0,1.0,1.0);
glClearDepth(1.0f);
glEnable(GL_DEPTH_TEST);
glDepthFunc(GL_LEQUAL);
glShadeModel(GL_SMOOTH);
}

void track()
{
glPushMatrix();
glLoadIdentity();
glTranslatef(0,translate,0);
	glBegin(GL_QUADS);
      	glColor3f(0.0f, 0.0f, 0.0f);
		glVertex3f(300.0,-600.0,-1.0);
		glVertex3f(600.0,-600.0,-1.0);
		glVertex3f(600.0,600.0,-1.0);
		glVertex3f(300.0,600.0,-1.0);
      	glEnd();

//stripes
	glBegin(GL_QUADS);
      	glColor3f(1.0f, 1.0f, 1.0f);
		
		glVertex3f(445.0,-670,-1.0);
		glVertex3f(455.0,-670,-1.0);
		glVertex3f(455.0,-610.0,-1.0);
		glVertex3f(445.0,-610.0,-1.0);

		glVertex3f(445.0,-560,-1.0);
		glVertex3f(455.0,-560,-1.0);
		glVertex3f(455.0,-500.0,-1.0);
		glVertex3f(445.0,-500.0,-1.0);

		glVertex3f(445.0,-440,-1.0);
		glVertex3f(455.0,-440,-1.0);
		glVertex3f(455.0,-380.0,-1.0);
		glVertex3f(445.0,-380.0,-1.0);

		glVertex3f(445.0,-330,-1.0);
		glVertex3f(455.0,-330,-1.0);
		glVertex3f(455.0,-270.0,-1.0);
		glVertex3f(445.0,-270.0,-1.0);

		glVertex3f(445.0,-220,-1.0);
		glVertex3f(455.0,-220,-1.0);
		glVertex3f(455.0,-160.0,-1.0);
		glVertex3f(445.0,-160.0,-1.0);

		glVertex3f(445.0,-110,-1.0);
		glVertex3f(455.0,-110,-1.0);
		glVertex3f(455.0,-50.0,-1.0);
		glVertex3f(445.0,-50.0,-1.0);

		glVertex3f(445.0,0.0,-1.0);
		glVertex3f(455.0,0.0,-1.0);
		glVertex3f(455.0,60.0,-1.0);
		glVertex3f(445.0,60.0,-1.0);

		glVertex3f(445.0,110.0,-1.0);
		glVertex3f(455.0,110.0,-1.0);
		glVertex3f(455.0,180.0,-1.0);
		glVertex3f(445.0,180.0,-1.0);

		glVertex3f(445.0,230.0,-1.0);
		glVertex3f(455.0,230.0,-1.0);
		glVertex3f(455.0,290.0,-1.0);
		glVertex3f(445.0,290.0,-1.0);

		glVertex3f(445.0,340.0,-1.0);
		glVertex3f(455.0,340.0,-1.0);
		glVertex3f(455.0,400.0,-1.0);
		glVertex3f(445.0,400.0,-1.0);

		glVertex3f(445.0,450.0,-1.0);
		glVertex3f(455.0,450.0,-1.0);
		glVertex3f(455.0,510.0,-1.0);
		glVertex3f(445.0,510.0,-1.0);

		glVertex3f(445.0,560.0,-1.0);
		glVertex3f(455.0,560.0,-1.0);
		glVertex3f(455.0,620.0,-1.0);
		glVertex3f(445.0,620.0,-1.0);
      	glEnd();

glPopMatrix();
glFlush();
}

void car()
{
glPushMatrix();
glLoadIdentity();
glTranslatef(450.0,540,-1.0);
glRotatef(rotate,0.0,0.0,1.0);
glTranslatef(-450,-540,-1.0);
	glColor3f(0.0,1.0,1.0);
	glBegin(GL_QUADS);
		glVertex3f(420.0,500.0,-1.0);
		glVertex3f(480.0,500.0,-1.0);
		glVertex3f(480.0,580.0,-1.0);
		glVertex3f(420.0,580.0,-1.0);
	glEnd();
	glBegin(GL_TRIANGLES);
		glVertex3f(480.0,500.0,-1.0);
		glVertex3f(420.0,500.0,-1.0);
		glVertex3f(450.0,470.0,-1.0);
	glEnd();
glPopMatrix();
}


void track_hor()
{
glPushMatrix();
glLoadIdentity();
glTranslatef(-translate,0,0);
	glBegin(GL_QUADS);
      	glColor3f(0.0f, 0.0f, 0.0f);
		glVertex3f(-900,150,-1.0);
		glVertex3f(1900.0,150.0,-1.0);
		glVertex3f(1900.0,450.0,-1.0);
		glVertex3f(-900.0,450.0,-1.0);
      	glEnd();

//stripes
	glBegin(GL_QUADS);
      	glColor3f(1.0f, 1.0f, 1.0f);

		glVertex3f(0,295,-1.0);
		glVertex3f(60,295,-1.0);
		glVertex3f(60,305,-1.0);
		glVertex3f(0,305,-1.0);

		glVertex3f(110,295,-1.0);
		glVertex3f(170,295,-1.0);
		glVertex3f(170,305,-1.0);
		glVertex3f(110,305,-1.0);

		glVertex3f(220,295,-1.0);
		glVertex3f(280,295,-1.0);
		glVertex3f(280,305,-1.0);
		glVertex3f(220,305,-1.0);

		glVertex3f(330,295,-1.0);
		glVertex3f(390,295,-1.0);
		glVertex3f(390,305,-1.0);
		glVertex3f(330,305,-1.0);

		glVertex3f(440,295,-1.0);
		glVertex3f(500,295,-1.0);
		glVertex3f(500,305,-1.0);
		glVertex3f(440,305,-1.0);

		glVertex3f(550,295,-1.0);
		glVertex3f(610,295,-1.0);
		glVertex3f(610,305,-1.0);
		glVertex3f(550,305,-1.0);

		glVertex3f(660,295,-1.0);
		glVertex3f(710,295,-1.0);
		glVertex3f(710,305,-1.0);
		glVertex3f(660,305,-1.0);

		glVertex3f(760,295,-1.0);
		glVertex3f(820,295,-1.0);
		glVertex3f(820,305,-1.0);
		glVertex3f(760,305,-1.0);

		glVertex3f(870,295,-1.0);
		glVertex3f(930,295,-1.0);
		glVertex3f(930,305,-1.0);
		glVertex3f(870,305,-1.0);

		glVertex3f(980,295,-1.0);
		glVertex3f(1040,295,-1.0);
		glVertex3f(1040,305,-1.0);
		glVertex3f(980,305,-1.0);

		glVertex3f(1090,295,-1.0);
		glVertex3f(1150,295,-1.0);
		glVertex3f(1150,305,-1.0);
		glVertex3f(1090,305,-1.0);

		glVertex3f(1200,295,-1.0);
		glVertex3f(1260,295,-1.0);
		glVertex3f(1260,305,-1.0);
		glVertex3f(1200,305,-1.0);

		glVertex3f(1310,295,-1.0);
		glVertex3f(1370,295,-1.0);
		glVertex3f(1370,305,-1.0);
		glVertex3f(1310,305,-1.0);

		glVertex3f(1420,295,-1.0);
		glVertex3f(1480,295,-1.0);
		glVertex3f(1480,305,-1.0);
		glVertex3f(1420,305,-1.0);

		     	glEnd();

glPopMatrix();
glFlush();
}

void car_hor()
{
glPushMatrix();
glLoadIdentity();
glTranslatef(50.0,300,-1.0);
glRotatef(rotate,0.0,0.0,1.0);
glTranslatef(-50,-300,-1.0);
	glColor3f(0.0,1.0,1.0);
	glBegin(GL_QUADS);
		glVertex3f(20.0,270.0,-1.0);
		glVertex3f(20.0,330.0,-1.0);
		glVertex3f(100.0,330.0,-1.0);
		glVertex3f(100.0,270.0,-1.0);
	glEnd();
	glBegin(GL_TRIANGLES);
		glVertex3f(100.0,270.0,-1.0);
		glVertex3f(100.0,330.0,-1.0);
		glVertex3f(130.0,300.0,-1.0);
	glEnd();
glPopMatrix();
}

void display()
{
glClear(GL_COLOR_BUFFER_BIT | GL_DEPTH_BUFFER_BIT);
glMatrixMode(GL_MODELVIEW);
if(view == 0)
{
track();
car();
}
else if(view == 1)
{
track_hor();
car_hor();
}
glutSwapBuffers();
}

void reshape(GLsizei w,GLsizei h)
{
if(h == 0 )
h = 1;
GLfloat aspect = GLfloat(w) / GLfloat(h);
glViewport(0,0,w,h);
glMatrixMode(GL_PROJECTION);
glLoadIdentity();
glOrtho(0,w,h,0,0.1f,100.0f);
//gluPerspective(90.0f,aspect,0.1f,100.0f);
}

void specialKeys( int key, int x, int y ) {
  if (key == GLUT_KEY_RIGHT)
   rotate+=5; 
  else if (key == GLUT_KEY_LEFT)
    rotate-=5;
  else if (key == GLUT_KEY_UP)
	{
	if(translate == 600)
	translate =300;
	else 
    translate+=5;
	}
  else if (key == GLUT_KEY_DOWN)
	if(translate == 0)
	translate =0;
	else
    	translate-=5;

	else if(key == GLUT_KEY_F1)
	view = ! view;
  glutPostRedisplay();
}

int main(int argc,char *argv[])
{
glutInit(&argc, argv);
glutInitDisplayMode (GLUT_DOUBLE);
glutInitWindowSize (900, 600);
glutInitWindowPosition (10, 10);
glutCreateWindow ("CAR");
init();
glutDisplayFunc(display);
glutReshapeFunc(reshape);
glutSpecialFunc(specialKeys);
glutMainLoop();
return 0;
}
