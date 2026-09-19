<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qga2a08ds.css';
import '../../css/m/m4g_1cb9m.css';
import '../../css/p/pyv3w0uuc.css';
import '../../css/s/switkv-0r.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline--alerted clr-i-outline-path-1--alerted qga2a08ds"/><path class="clr-i-outline--alerted clr-i-outline-path-2--alerted m4g_1cb9m"/><path class="clr-i-outline--alerted clr-i-outline-path-3--alerted pyv3w0uuc"/><path class="clr-i-alert clr-i-outline--alerted clr-i-outline-path-4--alerted switkv-0r"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:upload-cloud-outline-alerted" {...props}></Icon>
