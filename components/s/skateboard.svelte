<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/va4ask2uv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="va4ask2uv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:skateboard" {...props}></Icon>
