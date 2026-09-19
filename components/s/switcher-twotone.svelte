<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pck6pgbpl.css';
import '../../css/v/vh5zprbhd.css';
import '../../css/n/nf8po2uuu.css';
import '../../css/x/x2bo9tb4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pck6pgbpl"/><path class="vh5zprbhd"/><path class="nf8po2uuu"/><path class="x2bo9tb4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:switcher-twotone" {...props}></Icon>
