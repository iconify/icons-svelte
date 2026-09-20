<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxmajcb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cxmajcb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:selection-ellipse-remove" {...props}></Icon>
