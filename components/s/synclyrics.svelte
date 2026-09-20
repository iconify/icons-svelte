<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pj1lvn23t.css';
import '../../css/e/eionscb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pj1lvn23t"/><path class="eionscb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:synclyrics" {...props}></Icon>
