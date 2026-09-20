<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfo81w0ec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mfo81w0ec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:umbrella-line" {...props}></Icon>
