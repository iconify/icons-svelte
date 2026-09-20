<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff9rqab3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ff9rqab3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:user-search-line" {...props}></Icon>
