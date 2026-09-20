<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jch2jjbcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jch2jjbcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yamtrack-dark" {...props}></Icon>
