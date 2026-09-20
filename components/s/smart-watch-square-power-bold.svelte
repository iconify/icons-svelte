<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qz0rugjke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qz0rugjke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:smart-watch-square-power-bold" {...props}></Icon>
