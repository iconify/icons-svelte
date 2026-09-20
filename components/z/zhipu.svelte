<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtvfxacyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dtvfxacyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:zhipu" {...props}></Icon>
