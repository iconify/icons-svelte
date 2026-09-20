<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo98i2bnx.css';
import '../../css/t/tiid34lxq.css';
import '../../css/c/cus_5pahm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eo98i2bnx"/><path class="tiid34lxq"/><path class="cus_5pahm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:srk" {...props}></Icon>
