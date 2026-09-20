<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fucl7wbdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fucl7wbdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:speaker-line" {...props}></Icon>
