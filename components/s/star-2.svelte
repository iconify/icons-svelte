<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngt5p8b-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ngt5p8b-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:star-2" {...props}></Icon>
