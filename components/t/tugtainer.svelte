<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8l_-fb_k.css';
import '../../css/j/js4-qccyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j8l_-fb_k"/><path class="js4-qccyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tugtainer" {...props}></Icon>
