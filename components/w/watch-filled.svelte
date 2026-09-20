<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/moz6u8bdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="moz6u8bdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:watch-filled" {...props}></Icon>
