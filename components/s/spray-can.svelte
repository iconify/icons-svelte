<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1cswyb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h1cswyb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:spray-can" {...props}></Icon>
