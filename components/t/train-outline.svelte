<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcay3q_jj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lcay3q_jj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:train-outline" {...props}></Icon>
