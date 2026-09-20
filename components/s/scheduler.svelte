<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ooryjftqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ooryjftqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:scheduler" {...props}></Icon>
