<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/num_bkpuw.css';
import '../../css/b/bpv7jubps.css';
import '../../css/o/okk3kca1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="num_bkpuw"/><path class="bpv7jubps"/><path class="okk3kca1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:wifi-bridge" {...props}></Icon>
