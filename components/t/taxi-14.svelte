<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6tf23b2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="n6tf23b2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:taxi-14" {...props}></Icon>
