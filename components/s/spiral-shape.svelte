<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1c8i9qfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n1c8i9qfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:spiral-shape" {...props}></Icon>
