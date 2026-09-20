<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmdg2lbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="gmdg2lbjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:wind-beaufort-9" {...props}></Icon>
