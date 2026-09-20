<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yejv2fbfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yejv2fbfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:trophy-solid" {...props}></Icon>
