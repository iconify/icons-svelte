<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6agol35u.css';
import '../../css/p/pd8yij20i.css';
import '../../css/x/xrgtxcs3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6agol35u"/><path class="pd8yij20i"/><path clip-rule="evenodd" class="xrgtxcs3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:window-frame-bold" {...props}></Icon>
