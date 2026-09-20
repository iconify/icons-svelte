<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlv4y2bye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tlv4y2bye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:taobao" {...props}></Icon>
