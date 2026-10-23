<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6z2cnbrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g6z2cnbrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:x-line-top" {...props}></Icon>
