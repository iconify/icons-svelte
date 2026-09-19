<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcd_a183m.css';
import '../../css/j/j4rbxcc2v.css';
import '../../css/h/hmtgkjzwx.css';
import '../../css/b/b9ptyaccn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bcd_a183m"/><path class="j4rbxcc2v"/><path class="hmtgkjzwx"/><path class="b9ptyaccn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:spine-label" {...props}></Icon>
