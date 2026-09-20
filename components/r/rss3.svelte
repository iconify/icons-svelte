<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjv6_i5tk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hjv6_i5tk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:rss3" {...props}></Icon>
