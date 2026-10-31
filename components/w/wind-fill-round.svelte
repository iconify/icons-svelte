<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyscxebgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qyscxebgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:wind-fill-round" {...props}></Icon>
