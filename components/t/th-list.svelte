<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xip4mfbup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="xip4mfbup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:th-list" {...props}></Icon>
