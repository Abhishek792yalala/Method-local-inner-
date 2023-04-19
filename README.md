# Method-local-inner-
class Outer{

    void m1() {

        class Inner {

            void innermet() {

                System.out.println("methods local inner");

            }

        }

            Inner i = new Inner();

            i.innermet();

        }

    public static void main(String ... args){

        new Outer().m1();

    }

}

/*

methods local inner

 */
