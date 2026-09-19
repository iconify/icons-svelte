<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/u/urmicr44l.css';
import '../../css/n/nz6tfcbdx.css';
import '../../css/f/f1dep5d6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="urmicr44l"/><path class="nz6tfcbdx"/><path class="f1dep5d6u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:video-projector" {...props}></Icon>
