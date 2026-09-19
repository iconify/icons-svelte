<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyfts6bxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wyfts6bxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:websitebuilder" {...props}></Icon>
