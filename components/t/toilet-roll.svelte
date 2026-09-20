<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/d/dzgli20pz.css';
import '../../css/e/el85fgywn.css';
import '../../css/o/oootjbbym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><ellipse class="dzgli20pz"/><ellipse class="el85fgywn"/><path class="oootjbbym"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:toilet-roll" {...props}></Icon>
