<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb4kiwbzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wb4kiwbzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:torii-on-square" {...props}></Icon>
