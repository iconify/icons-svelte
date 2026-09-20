<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agn34nbcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="agn34nbcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:speakap" {...props}></Icon>
