<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlwfzf7fp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlwfzf7fp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:volume-high-fill-round" {...props}></Icon>
