<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj0mwubcb.css';
import '../../css/q/qm3xmebmn.css';
import '../../css/s/s-rrjubfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="oj0mwubcb"/><path class="qm3xmebmn"/><path class="s-rrjubfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:verified" {...props}></Icon>
