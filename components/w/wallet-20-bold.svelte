<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8ckwu0tw.css';
import '../../css/q/qgpi-ab8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s8ckwu0tw"/><path class="qgpi-ab8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wallet-20-bold" {...props}></Icon>
