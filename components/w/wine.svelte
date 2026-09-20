<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f__wo6bdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f__wo6bdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:wine" {...props}></Icon>
