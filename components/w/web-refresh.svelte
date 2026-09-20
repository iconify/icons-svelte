<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-dcdt1ug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-dcdt1ug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:web-refresh" {...props}></Icon>
