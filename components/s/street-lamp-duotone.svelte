<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo2ys05zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jo2ys05zc primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:street-lamp-duotone" {...props}></Icon>
