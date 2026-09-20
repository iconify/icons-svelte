<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqep6zwwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uqep6zwwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:star" {...props}></Icon>
