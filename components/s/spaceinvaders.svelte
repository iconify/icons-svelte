<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8isedb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":768};
const content = `<path class="w8isedb1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:spaceinvaders" {...props}></Icon>
