<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8eah7ecu.css';
import '../../css/j/jk9k79i2a.css';
import '../../css/n/npy1bcc-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="c8eah7ecu"/><path class="jk9k79i2a"/><path class="npy1bcc-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:unity" {...props}></Icon>
