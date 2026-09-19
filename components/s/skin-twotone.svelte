<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm5rxtu_s.css';
import '../../css/y/yqxcomdtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lm5rxtu_s"/><path class="yqxcomdtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:skin-twotone" {...props}></Icon>
