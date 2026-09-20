<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_264jbws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_264jbws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:toy-brick-location-outline" {...props}></Icon>
