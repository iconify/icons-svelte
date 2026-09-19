<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/z/zv06l1bpv.css';
import '../../css/h/hcafqxmbj.css';
import '../../css/k/kdt1gpbcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<g class="d2kvgvbvc"><path class="zv06l1bpv"/><path class="hcafqxmbj"/><path class="kdt1gpbcl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:terraform" {...props}></Icon>
