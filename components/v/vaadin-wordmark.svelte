<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwqxb2ble.css';
import '../../css/d/dibzppbzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="qwqxb2ble"/><path class="dibzppbzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:vaadin-wordmark" {...props}></Icon>
