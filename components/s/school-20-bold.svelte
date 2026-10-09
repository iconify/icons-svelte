<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aw_sajbrv.css';
import '../../css/u/uiz_pybsm.css';
import '../../css/p/p0r2mw_md.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="aw_sajbrv"/><path class="uiz_pybsm"/><path class="p0r2mw_md"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:school-20-bold" {...props}></Icon>
