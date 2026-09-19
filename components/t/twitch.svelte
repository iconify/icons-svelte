<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axftgxx0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1600,"height":1664};
const content = `<path class="axftgxx0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:twitch" {...props}></Icon>
