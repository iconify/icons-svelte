<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvaz16bmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="yvaz16bmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:triangle-with-rounded-corners" {...props}></Icon>
