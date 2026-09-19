<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh36zabkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wh36zabkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sentry-gun" {...props}></Icon>
