<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffyaq1wcl.css';
import '../../css/i/i-d09ab5o.css';
import '../../css/p/p7o_o6bnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ffyaq1wcl"/><path class="i-d09ab5o"/><path class="p7o_o6bnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:settings-check" {...props}></Icon>
