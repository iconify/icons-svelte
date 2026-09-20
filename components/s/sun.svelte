<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kol8oy98e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kol8oy98e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:sun" {...props}></Icon>
