<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsd0dqg8h.css';
import '../../css/f/fj0-3lbac.css';
import '../../css/f/f0-68acbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wsd0dqg8h"/><path class="fj0-3lbac"/><path class="f0-68acbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:torque-wrench-20" {...props}></Icon>
