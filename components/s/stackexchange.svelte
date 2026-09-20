<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdgu9obmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdgu9obmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:stackexchange" {...props}></Icon>
