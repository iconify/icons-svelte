<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7v90bbbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7v90bbbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:view-column-outline" {...props}></Icon>
