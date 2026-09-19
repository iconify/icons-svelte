<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0-6anw0t.css';
import '../../css/j/jr1xz7b-w.css';
import '../../css/l/l2k-wqsww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s0-6anw0t"/><path class="jr1xz7b-w"/><path class="l2k-wqsww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:wireless-checkout" {...props}></Icon>
