<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy3m-2b8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sy3m-2b8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:sword-line" {...props}></Icon>
