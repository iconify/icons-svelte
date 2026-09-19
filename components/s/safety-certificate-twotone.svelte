<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm3xmebmn.css';
import '../../css/w/wtww-cbab.css';
import '../../css/k/k3hg-_0hy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qm3xmebmn"/><path class="wtww-cbab"/><path class="k3hg-_0hy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:safety-certificate-twotone" {...props}></Icon>
