<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahdk97bpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahdk97bpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:shadow-tech-logo-solid" {...props}></Icon>
