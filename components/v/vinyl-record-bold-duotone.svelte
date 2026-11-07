<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b85oo4swx.css';
import '../../css/f/fdq8872og.css';
import '../../css/q/q14qdhbhn.css';
import '../../css/k/kjtd21bxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b85oo4swx"/><path class="fdq8872og"/><path class="q14qdhbhn"/><path clip-rule="evenodd" class="kjtd21bxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:vinyl-record-bold-duotone" {...props}></Icon>
