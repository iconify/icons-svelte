<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyy1-b-7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gyy1-b-7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:translate-2" {...props}></Icon>
