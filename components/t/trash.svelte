<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vld3eebqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vld3eebqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:trash" {...props}></Icon>
