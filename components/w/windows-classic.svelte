<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwe4--b9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwe4--b9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:windows-classic" {...props}></Icon>
