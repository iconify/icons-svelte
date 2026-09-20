<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba63usbyw.css';
import '../../css/f/f3e8vhbzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ba63usbyw"/><path class="f3e8vhbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:slr" {...props}></Icon>
