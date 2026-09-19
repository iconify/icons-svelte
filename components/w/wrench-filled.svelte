<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qf66ysvcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="qf66ysvcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:wrench-filled" {...props}></Icon>
