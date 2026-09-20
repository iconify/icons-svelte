<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp-m33bou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pp-m33bou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:threat-usb-remix" {...props}></Icon>
