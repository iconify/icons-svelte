<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbpwy0b8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cbpwy0b8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:server-square-filled" {...props}></Icon>
