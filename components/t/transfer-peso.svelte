<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xli4t7b_v.css';
import '../../css/d/dwyzddbwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xli4t7b_v"/><path class="dwyzddbwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:transfer-peso" {...props}></Icon>
