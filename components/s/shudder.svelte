<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyl1ebdmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yyl1ebdmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:shudder" {...props}></Icon>
