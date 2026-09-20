<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw0kxo5rm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gw0kxo5rm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:sim3" {...props}></Icon>
