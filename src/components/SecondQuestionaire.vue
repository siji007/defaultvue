<template>
    <div class="container">
        <div class="mt-4">
            <button class="btn btn-dark btn-sm"><p>Section 2 of 2</p></button>
        </div>
        <div class="p-4 mt-4 rounded-lg" style="background-color:#8FE58E;">
            <p class="text-2xl">A STUDY INTO THE NEGATIVE INFLUENCE OF INFORMATION TECHNOLOGY ON CHILD EDUCATION (A CASE STUDY OF SECONDARY SCHOOLS IN ILORIN SOUTH)</p>
        </div>

        <div class="p-4 mt-4 rounded-t-lg" style="background-color:#8FE58E;">
            <p class="text-2xl">NEGATIVE INFLUENCE OF INFORMATION TECHNOLOGY ON LEVEL OF CHILD EDUCATION</p>
        </div>
        <div class="rounded-b-lg" style="background-color:#8FE58E;">
            <p class="px-4 pb-4">
                Please respond to each of the following statements what most represents your agreement or disagreement to the items.    
            </p>
        </div>

        <!-- <div class="p-4 mt-4">
            <div class="flex justify-between">
                <div>Student</div>
                <div>Strongly Diasgree</div>
                <div>Diasgree</div>
                <div>Agree</div>
                <div>Strongly Agree</div>
            </div>
        </div> -->
        <div class=" mt-4">
            <!-- <form action="" @submit.prevent="submit"> -->
                <div class="form-group p-4 rounded-lg" style="background-color:#8FE58E;">
                    <label for="" class="text-large font-bold">Get distracted in class when they bring their phones to class</label> <br>
                    <input type="radio" required name="response1" id="sd"> <span class="ml-2">Strongly Disagree</span><br>
                    <input type="radio" required name="response1" id="d"> <span class="ml-2">Disagree</span><br>
                    <input type="radio" required name="response1" id="a"> <span class="ml-2">Agree</span><br>
                    <input type="radio" required name="response1" id="a"> <span class="ml-2">Strong Agree</span><br>
                </div>
                

                <div class="form-group p-4 mb-4 rounded-lg" style="background-color:#8FE58E;">
                    <label for="" class="text-large font-bold">Get distracted by information technology media after school</label> <br>
                    <input type="radio" required name="response2" id="sd"> <span class="ml-2">Strongly Disagree</span><br>
                    <input type="radio" required name="response2" id="d"> <span class="ml-2">Disagree</span><br>
                    <input type="radio" required name="response2" id="a"> <span class="ml-2">Agree</span><br>
                    <input type="radio" required name="response2" id="a"> <span class="ml-2">Strong Agree</span><br>
                </div>

                <div class="form-group p-4 mt-4 rounded-lg" style="background-color:#8FE58E;">
                    <label for="" class="text-large font-bold">Visit game centers or play games more than reading their books.</label> <br>
                    <input type="radio" required name="response3" id="sd"> <span class="ml-2">Strongly Disagree</span><br>
                    <input type="radio" required name="response3" id="d"> <span class="ml-2">Disagree</span><br>
                    <input type="radio" required name="response3" id="a"> <span class="ml-2">Agree</span><br>
                    <input type="radio" required name="response3" id="a"> <span class="ml-2">Strong Agree</span><br>
                </div>

                <div class="form-group p-4 mt-4 rounded-lg" style="background-color:#8FE58E;">
                    <label for="" class="text-large font-bold">Are more active on social media than their academics.</label> <br>
                    <input type="radio" required name="response4" id="sd"> <span class="ml-2">Strongly Disagree</span><br>
                    <input type="radio" required name="response4" id="d"> <span class="ml-2">Disagree</span><br>
                    <input type="radio" required name="response4" id="a"> <span class="ml-2">Agree</span><br>
                    <input type="radio" required name="response4" id="a"> <span class="ml-2">Strong Agree</span><br>
                </div>

                <div class="form-group p-4 mt-4 rounded-lg" style="background-color:#8FE58E;">
                    <label for="" class="text-large font-bold">Are exposed to pornographic information which affects their academics negatively.</label> <br>
                    <input type="radio" required name="response5" id="sd"> <span class="ml-2">Strongly Disagree</span><br>
                    <input type="radio" required name="response5" id="d"> <span class="ml-2">Disagree</span><br>
                    <input type="radio" required name="response5" id="a"> <span class="ml-2">Agree</span><br>
                    <input type="radio" required name="response5" id="a"> <span class="ml-2">Strong Agree</span><br>
                </div>

                <div class="form-group p-4 mt-4 rounded-lg" style="background-color:#8FE58E;">
                    <label for="" class="text-large font-bold">Are addicted to television after schools hours.</label> <br>
                    <input type="radio" required name="response6" id="sd"> <span class="ml-2">Strongly Disagree</span><br>
                    <input type="radio" required name="response6" id="d"> <span class="ml-2">Disagree</span><br>
                    <input type="radio" required name="response6" id="a"> <span class="ml-2">Agree</span><br>
                    <input type="radio" required name="response6" id="a"> <span class="ml-2">Strong Agree</span><br>
                </div>

                <div class="form-group p-4 mt-4 rounded-lg" style="background-color:#8FE58E;">
                    <label for="" class="text-large font-bold">Use mobile phones for examination malpractice.</label> <br>
                    <input type="radio" required name="response7" id="sd"> <span class="ml-2">Strongly Disagree</span><br>
                    <input type="radio" required name="response7" id="d"> <span class="ml-2">Disagree</span><br>
                    <input type="radio" required name="response7" id="a"> <span class="ml-2">Agree</span><br>
                    <input type="radio" required name="response7" id="a"> <span class="ml-2">Strong Agree</span><br>
                </div>

                <div class="form-group p-4 mt-4 rounded-lg" style="background-color:#8FE58E;">
                    <label for="" class="text-large font-bold">Are distracted by other mobile or computer features when attending online classes.</label> <br>
                    <input type="radio" required name="response8" id="sd"> <span class="ml-2">Strongly Disagree</span><br>
                    <input type="radio" required name="response8" id="d"> <span class="ml-2">Disagree</span><br>
                    <input type="radio" required name="response8" id="a"> <span class="ml-2">Agree</span><br>
                    <input type="radio" required name="response8" id="a"> <span class="ml-2">Strong Agree</span><br>
                </div>

                <div class="form-group p-4 mt-4 rounded-lg" style="background-color:#8FE58E;">
                    <label for="" class="text-large font-bold">Are addicted to movies or shows on their devices.</label> <br>
                    <input type="radio" required name="response9" id="sd"> <span class="ml-2">Strongly Disagree</span><br>
                    <input type="radio" required name="response9" id="d"> <span class="ml-2">Disagree</span><br>
                    <input type="radio" required name="response9" id="a"> <span class="ml-2">Agree</span><br>
                    <input type="radio" required name="response9" id="a"> <span class="ml-2">Strong Agree</span><br>
                </div>

                <div class="form-group p-4 mt-4 rounded-lg" style="background-color:#8FE58E;">
                    <label for="" class="text-large font-bold">Are distracted by listening to music in class.</label> <br>
                    <input type="radio" required name="response10" id="sd"> <span class="ml-2">Strongly Disagree</span><br>
                    <input type="radio" required name="response10" id="d"> <span class="ml-2">Disagree</span><br>
                    <input type="radio" required name="response10" id="a"> <span class="ml-2">Agree</span><br>
                    <input type="radio" required name="response10" id="a"> <span class="ml-2">Strong Agree</span><br>
                </div>

                <div class="form-group p-4 mt-4 rounded-lg" style="background-color:#8FE58E;">
                    <label for="" class="text-large font-bold">Use the internet to download unnecessary information.</label> <br>
                    <input type="radio" required name="response11" id="sd"> <span class="ml-2">Strongly Disagree</span><br>
                    <input type="radio" required name="response11" id="d"> <span class="ml-2">Disagree</span><br>
                    <input type="radio" required name="response11" id="a"> <span class="ml-2">Agree</span><br>
                    <input type="radio" required name="response11" id="a"> <span class="ml-2">Strong Agree</span><br>
                </div>

                <div class="form-group p-4 mt-4 rounded-lg" style="background-color:#8FE58E;">
                    <label for="" class="text-large font-bold">Are exposed to moral corruption through the internet.</label> <br>
                    <input type="radio" required name="response11" id="sd"> <span class="ml-2">Strongly Disagree</span><br>
                    <input type="radio" required name="response11" id="d"> <span class="ml-2">Disagree</span><br>
                    <input type="radio" required name="response11" id="a"> <span class="ml-2">Agree</span><br>
                    <input type="radio" required name="response11" id="a"> <span class="ml-2">Strong Agree</span><br>
                </div>

                <div class="form-group p-4 mt-4 rounded-lg" style="background-color:#8FE58E;">
                    <label for="" class="text-large font-bold">Are exposed to gambling through technology and affects their education.</label> <br>
                    <input type="radio" required name="response12" id="sd"> <span class="ml-2">Strongly Disagree</span><br>
                    <input type="radio" required name="response12" id="d"> <span class="ml-2">Disagree</span><br>
                    <input type="radio" required name="response12" id="a"> <span class="ml-2">Agree</span><br>
                    <input type="radio" required name="response12" id="a"> <span class="ml-2">Strong Agree</span><br>
                </div>

                <div class="form-group p-4 mt-4 rounded-lg" style="background-color:#8FE58E;">
                    <label for="" class="text-large font-bold">Are exposed to internet scam which affects their education.</label> <br>
                    <input type="radio" required name="response13" id="sd"> <span class="ml-2">Strongly Disagree</span><br>
                    <input type="radio" required name="response13" id="d"> <span class="ml-2">Disagree</span><br>
                    <input type="radio" required name="response13" id="a"> <span class="ml-2">Agree</span><br>
                    <input type="radio" required name="response13" id="a"> <span class="ml-2">Strong Agree</span><br>
                </div>

                <div class="form-group p-4 mt-4 rounded-lg" style="background-color:#8FE58E;">
                    <label for="" class="text-large font-bold">Have become lazy in their academics since they get most information online.</label> <br>
                    <input type="radio" required name="response14" id="sd"> <span class="ml-2">Strongly Disagree</span><br>
                    <input type="radio" required name="response14" id="d"> <span class="ml-2">Disagree</span><br>
                    <input type="radio" required name="response14" id="a"> <span class="ml-2">Agree</span><br>
                    <input type="radio" required name="response14" id="a"> <span class="ml-2">Strong Agree</span><br>
                </div>

                <div class="form-group p-4 mt-4 rounded-lg" style="background-color:#8FE58E;">
                    <label for="" class="text-large font-bold">Are misguided academically due to wrong information online.</label> <br>
                    <input type="radio" required name="response15" id="sd"> <span class="ml-2">Strongly Disagree</span><br>
                    <input type="radio" required name="response15" id="d"> <span class="ml-2">Disagree</span><br>
                    <input type="radio" required name="response15" id="a"> <span class="ml-2">Agree</span><br>
                    <input type="radio" required name="response15" id="a"> <span class="ml-2">Strong Agree</span><br>
                </div>

                <div class="form-group p-4 mt-4 rounded-lg" style="background-color:#8FE58E;">
                    <label for="" class="text-large font-bold">Lose the habit to write due to excessive use of laptops and mobile phones.</label> <br>
                    <input type="radio" required name="response16" id="sd"> <span class="ml-2">Strongly Disagree</span><br>
                    <input type="radio" required name="response16" id="d"> <span class="ml-2">Disagree</span><br>
                    <input type="radio" required name="response16" id="a"> <span class="ml-2">Agree</span><br>
                    <input type="radio" required name="response16" id="a"> <span class="ml-2">Strong Agree</span><br>
                </div>

                <div class="form-group p-4 mt-4 rounded-lg" style="background-color:#8FE58E;">
                    <label for="" class="text-large font-bold">Are more likely to loose their data on laptops or mobile phones than having physical books.</label> <br>
                    <input type="radio" required name="response17" id="sd"> <span class="ml-2">Strongly Disagree</span><br>
                    <input type="radio" required name="response17" id="d"> <span class="ml-2">Disagree</span><br>
                    <input type="radio" required name="response17" id="a"> <span class="ml-2">Agree</span><br>
                    <input type="radio" required name="response17" id="a"> <span class="ml-2">Strong Agree</span><br>
                </div>

                <div class="form-group p-4 mt-4 rounded-lg" style="background-color:#8FE58E;">
                    <label for="" class="text-large font-bold">Are more serious in attending physical classes than online classes.</label> <br>
                    <input type="radio" required name="response18" id="sd"> <span class="ml-2">Strongly Disagree</span><br>
                    <input type="radio" required name="response18" id="d"> <span class="ml-2">Disagree</span><br>
                    <input type="radio" required name="response18" id="a"> <span class="ml-2">Agree</span><br>
                    <input type="radio" required name="response18" id="a"> <span class="ml-2">Strong Agree</span><br>
                </div>

                <div class="form-group p-4 mt-4 rounded-lg" style="background-color:#8FE58E;">
                    <label for="" class="text-large font-bold">Are motivated to read physical books than reading from electronic devices.</label> <br>
                    <input type="radio" required name="response19" id="sd"> <span class="ml-2">Strongly Disagree</span><br>
                    <input type="radio" required name="response19" id="d"> <span class="ml-2">Disagree</span><br>
                    <input type="radio" required name="response19" id="a"> <span class="ml-2">Agree</span><br>
                    <input type="radio" required name="response19" id="a"> <span class="ml-2">Strong Agree</span><br>
                </div>

                <div class="mt-4 pb-8">
                    <!-- <router-link to="/section_1" tag="button"> -->
                    <button type="button" @click="show" class="btn btn-light">Back</button>
                    <!-- </router-link> -->

                    <!-- <router-link to="/success_page" tag="button"> -->
                        <button class="btn ml-4" @click="check" style="background-color:#8FE58E;">Submit</button>
                    <!-- </router-link> -->
                </div>

            <!-- </form> -->
        </div>
    </div>
</template>

<script>
// import FirstQuestionaire from '@/components/FirstQuestionaire'
export default {
    components:{
        // FirstQuestionaire
    },
    methods:{
        submit(){
            console.log('Done');
        },
        
    }
}
</script>