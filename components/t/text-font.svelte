<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8eqpxbfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l8eqpxbfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:text-font" {...props}></Icon>
