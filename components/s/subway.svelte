<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmhu_wbhm.css';
import '../../css/c/cfnmk50zf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rmhu_wbhm"/><path class="cfnmk50zf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:subway" {...props}></Icon>
