<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co0iqo8wk.css';
import '../../css/g/gcopb3ilo.css';
import '../../css/k/k4fizwbwr.css';
import '../../css/q/qv6-upvsv.css';
import '../../css/y/yv_ow6bdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="co0iqo8wk"/><path class="gcopb3ilo"/><path class="k4fizwbwr"/><path class="qv6-upvsv"/><path class="yv_ow6bdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ufo-2-bold" {...props}></Icon>
