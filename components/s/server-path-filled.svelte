<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezof65bpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ezof65bpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:server-path-filled" {...props}></Icon>
