<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8rrqslmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q8rrqslmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:vr-cardboard" {...props}></Icon>
