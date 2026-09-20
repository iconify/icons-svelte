<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/haieeyb3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="haieeyb3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:search" {...props}></Icon>
