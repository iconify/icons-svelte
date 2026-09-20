<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3lln_ecx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3lln_ecx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:text" {...props}></Icon>
