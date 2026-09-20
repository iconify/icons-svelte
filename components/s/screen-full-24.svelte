<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcjiy60hl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xcjiy60hl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:screen-full-24" {...props}></Icon>
