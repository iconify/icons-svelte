<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov8walbuy.css';
import '../../css/f/fwj4s1b_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ov8walbuy"/><path clip-rule="evenodd" class="fwj4s1b_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:wallet-detailed-fill" {...props}></Icon>
