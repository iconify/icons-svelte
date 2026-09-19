<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7drbab-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p7drbab-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:up-two" {...props}></Icon>
