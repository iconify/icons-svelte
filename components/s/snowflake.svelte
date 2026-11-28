<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi2i9ubvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pi2i9ubvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:snowflake" {...props}></Icon>
