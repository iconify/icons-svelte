<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9r4z__4k.css';
import '../../css/z/z8e8kub5u.css';
import '../../css/g/gq7xqhlwu.css';
import '../../css/o/o6k2-ibor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f9r4z__4k"/><path class="z8e8kub5u"/><circle class="gq7xqhlwu"/><path class="o6k2-ibor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:wave-direction" {...props}></Icon>
