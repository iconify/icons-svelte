<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p41-95gdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p41-95gdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:xml" {...props}></Icon>
