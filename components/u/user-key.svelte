<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4ereq4fl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e4ereq4fl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:user-key" {...props}></Icon>
