<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wuazwe1im.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wuazwe1im"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:socialnetwork" {...props}></Icon>
