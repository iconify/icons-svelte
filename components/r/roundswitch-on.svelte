<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e658-774s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path clip-rule="evenodd" class="e658-774s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:roundswitch-on" {...props}></Icon>
