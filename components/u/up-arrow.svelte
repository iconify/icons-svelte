<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp-6ebbmc.css';
import '../../css/l/ljs5lpfqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="gp-6ebbmc"/><path class="ljs5lpfqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:up-arrow" {...props}></Icon>
