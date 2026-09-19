<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5xtybbsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i5xtybbsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:socket-filled" {...props}></Icon>
