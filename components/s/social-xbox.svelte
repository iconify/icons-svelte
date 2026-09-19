<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wn38p6dkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="wn38p6dkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-xbox" {...props}></Icon>
