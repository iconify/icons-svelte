<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct5bir.css';
import '../../css/a/a0m25c.css';
import '../../css/m/m2hv7f.css';
import '../../css/x/xf_gao.css';
import '../../css/d/d-3fqnuo.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ct5bir"/><path class="a0m25c m2hv7f"/><path class="a0m25c xf_gao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:steering" {...props}></Icon>
