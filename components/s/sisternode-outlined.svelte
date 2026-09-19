<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkz3kr8cu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rkz3kr8cu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:sisternode-outlined" {...props}></Icon>
