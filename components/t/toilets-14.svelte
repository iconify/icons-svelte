<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chqnloxdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="chqnloxdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:toilets-14" {...props}></Icon>
