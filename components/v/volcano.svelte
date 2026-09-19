<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euov_5bqj.css';
import '../../css/o/o_7ob93fj.css';
import '../../css/y/ysqt2irzb.css';
import '../../css/a/aermgf_ls.css';
import '../../css/s/s632r_bsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="euov_5bqj"/><path class="o_7ob93fj"/><path class="ysqt2irzb"/><path class="aermgf_ls"/><path class="s632r_bsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:volcano" {...props}></Icon>
