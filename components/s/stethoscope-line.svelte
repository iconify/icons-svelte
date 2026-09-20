<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alfk40bal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="alfk40bal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:stethoscope-line" {...props}></Icon>
