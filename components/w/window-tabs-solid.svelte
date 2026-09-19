<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt-c1iyft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bt-c1iyft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:window-tabs-solid" {...props}></Icon>
