<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpjdfxbzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wpjdfxbzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:text-align-right-01" {...props}></Icon>
