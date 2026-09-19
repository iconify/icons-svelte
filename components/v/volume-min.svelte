<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wel5m5zih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wel5m5zih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:volume-min" {...props}></Icon>
