<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omn5tm59o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="omn5tm59o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:web-asset" {...props}></Icon>
