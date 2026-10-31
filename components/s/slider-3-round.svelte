<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npedpf06a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="npedpf06a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:slider-3-round" {...props}></Icon>
