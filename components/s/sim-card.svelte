<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpeu335fl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="hpeu335fl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:sim-card" {...props}></Icon>
