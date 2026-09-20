<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1u2czauv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1u2czauv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sync-circle" {...props}></Icon>
