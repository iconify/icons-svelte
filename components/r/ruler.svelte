<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_z2pbckr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="d_z2pbckr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:ruler" {...props}></Icon>
