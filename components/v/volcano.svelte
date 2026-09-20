<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj-5f8bxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="oj-5f8bxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:volcano" {...props}></Icon>
