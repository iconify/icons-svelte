<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2c72nr_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u2c72nr_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shield-star" {...props}></Icon>
