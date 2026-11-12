<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iii3nbb6b.css';
import '../../css/s/sdij9c2vr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iii3nbb6b"/><path class="sdij9c2vr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sharkord-light" {...props}></Icon>
