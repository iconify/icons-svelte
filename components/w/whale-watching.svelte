<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1_9nob6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="f1_9nob6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:whale-watching" {...props}></Icon>
