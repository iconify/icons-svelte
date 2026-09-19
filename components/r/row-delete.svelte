<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/x/x03m03b7g.css';
import '../../css/p/pi8np5bgj.css';
import '../../css/u/umb8f1b3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="x03m03b7g"/><path class="pi8np5bgj"/><path class="umb8f1b3x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:row-delete" {...props}></Icon>
