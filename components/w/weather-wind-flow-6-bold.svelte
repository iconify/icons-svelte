<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8df8ibqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q8df8ibqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:weather-wind-flow-6-bold" {...props}></Icon>
