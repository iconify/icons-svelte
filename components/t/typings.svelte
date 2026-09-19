<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5mhk7llr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u5mhk7llr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:typings" {...props}></Icon>
