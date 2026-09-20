<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/boevr-yxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="boevr-yxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:up-2" {...props}></Icon>
