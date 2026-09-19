<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9usotbod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g9usotbod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:square" {...props}></Icon>
