<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg3m-ybnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vg3m-ybnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:sad-circle-filled" {...props}></Icon>
