<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnl2_bcrh.css';
import '../../css/f/flf8qs4fv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnl2_bcrh"/><path class="flf8qs4fv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:twtich" {...props}></Icon>
