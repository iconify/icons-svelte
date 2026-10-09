<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfgle7bjr.css';
import '../../css/v/v8-70c-7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wfgle7bjr"/><path class="v8-70c-7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:vertical-axis-turbine-20" {...props}></Icon>
