<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzoe01kfd.css';
import '../../css/q/qdd1rtb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pzoe01kfd"/><circle class="qdd1rtb9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:sunny-outline" {...props}></Icon>
