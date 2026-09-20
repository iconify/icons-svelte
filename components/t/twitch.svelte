<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4rcx6sjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e4rcx6sjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:twitch" {...props}></Icon>
