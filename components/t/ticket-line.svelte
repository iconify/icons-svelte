<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fs6v47kig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fs6v47kig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:ticket-line" {...props}></Icon>
