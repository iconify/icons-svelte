<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxjp031gi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zxjp031gi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:tower-of-babel" {...props}></Icon>
