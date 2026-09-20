<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu67n8t-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fu67n8t-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:rx-symbol-above-outstretched-hand" {...props}></Icon>
