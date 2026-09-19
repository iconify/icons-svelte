<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eekymj8ao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":24};
const content = `<path class="eekymj8ao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:usb" {...props}></Icon>
