<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9n0gb6of.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d9n0gb6of"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:up-and-down" {...props}></Icon>
