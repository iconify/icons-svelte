<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwinbcbgb.css';
import '../../css/l/lzqdc0rqk.css';
import '../../css/y/yepcn_hpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qwinbcbgb"/><path class="lzqdc0rqk"/><path class="yepcn_hpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:test-tube-20-bold" {...props}></Icon>
