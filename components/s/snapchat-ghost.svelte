<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je1zpsble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="je1zpsble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:snapchat-ghost" {...props}></Icon>
