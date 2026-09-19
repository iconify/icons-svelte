<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apfc86bot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="apfc86bot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:spray-can" {...props}></Icon>
