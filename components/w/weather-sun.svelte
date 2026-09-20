<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crh91xb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crh91xb0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:weather-sun" {...props}></Icon>
