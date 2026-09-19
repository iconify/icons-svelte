<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvxfi23oz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yvxfi23oz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:star" {...props}></Icon>
