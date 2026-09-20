<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfalo7bnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xfalo7bnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:text-recognition" {...props}></Icon>
