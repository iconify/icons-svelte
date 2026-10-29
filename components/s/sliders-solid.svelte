<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkf8rzb6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkf8rzb6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:sliders-solid" {...props}></Icon>
