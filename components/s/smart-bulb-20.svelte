<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewk2or1yh.css';
import '../../css/v/vuc2o48vf.css';
import '../../css/u/uofloxbgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ewk2or1yh"/><path class="vuc2o48vf"/><path class="uofloxbgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smart-bulb-20" {...props}></Icon>
