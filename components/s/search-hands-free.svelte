<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/das9g7b-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="das9g7b-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:search-hands-free" {...props}></Icon>
