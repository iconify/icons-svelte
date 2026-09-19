<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c16rm2tya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c16rm2tya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:up-two" {...props}></Icon>
