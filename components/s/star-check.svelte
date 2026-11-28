<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acfb4tdcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="acfb4tdcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:star-check" {...props}></Icon>
