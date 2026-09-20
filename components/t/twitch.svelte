<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm7fs1b4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="hm7fs1b4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:twitch" {...props}></Icon>
