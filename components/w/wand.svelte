<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydoijsblt.css';
import '../../css/k/k56jjpbhp.css';
import '../../css/m/m7oxax7lf.css';
import '../../css/s/svo4flnls.css';
import '../../css/c/c31ot8bha.css';
import '../../css/f/fjvx_cbrp.css';
import '../../css/v/v63j9u_kg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ydoijsblt"/><path class="k56jjpbhp"/><path class="m7oxax7lf"/><path class="svo4flnls"/><path class="c31ot8bha"/><path class="fjvx_cbrp"/><path class="v63j9u_kg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:wand" {...props}></Icon>
