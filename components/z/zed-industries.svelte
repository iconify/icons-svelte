<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl2p6pedi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vl2p6pedi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:zed-industries" {...props}></Icon>
