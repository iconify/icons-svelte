<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng6nzyr8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ng6nzyr8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:vpn-connection-remix" {...props}></Icon>
