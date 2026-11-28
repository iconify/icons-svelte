<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bajsucc6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bajsucc6j primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:scroll-duotone" {...props}></Icon>
