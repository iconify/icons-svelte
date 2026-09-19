<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk1ssk6fg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dk1ssk6fg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:telegram" {...props}></Icon>
