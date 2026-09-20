<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd9c8clmb.css';
import '../../css/m/mlljs5b8w.css';
import '../../css/z/zew23veae.css';
import '../../css/a/a-gf5y89p.css';
import '../../css/d/d8s3b-zbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vd9c8clmb"/><path class="mlljs5b8w"/><path class="zew23veae"/><path class="a-gf5y89p"/><path class="d8s3b-zbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-emojis:speaking-head" {...props}></Icon>
