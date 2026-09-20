<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov6hbkbhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ov6hbkbhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:rounded-triangle-down-outline" {...props}></Icon>
