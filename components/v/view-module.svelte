<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcgtlkb6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":368,"height":384};
const content = `<path class="xcgtlkb6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:view-module" {...props}></Icon>
