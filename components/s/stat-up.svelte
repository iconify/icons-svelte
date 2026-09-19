<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv-10c8zx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wv-10c8zx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:stat-up" {...props}></Icon>
