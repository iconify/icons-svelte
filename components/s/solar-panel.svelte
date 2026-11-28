<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9e3qgbin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y9e3qgbin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:solar-panel" {...props}></Icon>
