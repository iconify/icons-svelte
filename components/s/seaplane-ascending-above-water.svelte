<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk1wv5bck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pk1wv5bck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:seaplane-ascending-above-water" {...props}></Icon>
