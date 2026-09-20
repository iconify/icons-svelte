<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu8e57oik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nu8e57oik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:winamp" {...props}></Icon>
