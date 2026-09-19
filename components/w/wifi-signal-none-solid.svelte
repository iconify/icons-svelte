<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9n7pnb0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i9n7pnb0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:wifi-signal-none-solid" {...props}></Icon>
