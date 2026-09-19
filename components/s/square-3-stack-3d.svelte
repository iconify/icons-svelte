<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcj6hkb8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xcj6hkb8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:square-3-stack-3d" {...props}></Icon>
