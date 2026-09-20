<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htbbrjlzo.css';
import '../../css/h/hmqgikzpa.css';
import '../../css/h/howiqgbsw.css';
import '../../css/d/dhkuk8bie.css';
import '../../css/p/p1r_hs_-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="htbbrjlzo"/><path class="hmqgikzpa"/><circle transform="rotate(-44.781 37.124 22.122)" class="howiqgbsw"/><circle transform="rotate(-44.781 43.614 28.661)" class="dhkuk8bie"/><circle transform="rotate(-44.781 50.104 35.2)" class="p1r_hs_-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:ticket" {...props}></Icon>
