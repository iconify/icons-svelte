<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u57lmtb4w.css';
import '../../css/g/gprn__pii.css';
import '../../css/d/de8upybhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u57lmtb4w"/><path class="gprn__pii"/><path class="de8upybhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ticky" {...props}></Icon>
