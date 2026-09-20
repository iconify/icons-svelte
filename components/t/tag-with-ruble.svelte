<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au6cpbb4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="au6cpbb4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tag-with-ruble" {...props}></Icon>
