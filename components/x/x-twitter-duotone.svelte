<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9jm7-0vp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b9jm7-0vp primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:x-twitter-duotone" {...props}></Icon>
