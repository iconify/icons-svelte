<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skkxrhl2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="skkxrhl2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:wallet-3-filled" {...props}></Icon>
