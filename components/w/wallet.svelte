<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfimg1yuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfimg1yuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wallet" {...props}></Icon>
