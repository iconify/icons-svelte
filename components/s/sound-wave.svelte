<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygnhg0zau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ygnhg0zau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:sound-wave" {...props}></Icon>
