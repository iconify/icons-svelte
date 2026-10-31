<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx0oicvhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kx0oicvhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-chevron-double-up-round" {...props}></Icon>
