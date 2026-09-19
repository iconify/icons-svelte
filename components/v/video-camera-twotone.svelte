<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jib32ub8s.css';
import '../../css/q/qvm7p4brn.css';
import '../../css/d/d3r-gqy_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jib32ub8s"/><path class="qvm7p4brn"/><path class="d3r-gqy_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:video-camera-twotone" {...props}></Icon>
