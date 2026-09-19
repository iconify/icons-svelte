<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2o-8kr3y.css';
import '../../css/q/qx05z4bvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g2o-8kr3y"/><path class="qx05z4bvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:window" {...props}></Icon>
