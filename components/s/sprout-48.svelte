<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o51dot6hb.css';
import '../../css/y/ybcmecbwb.css';
import '../../css/r/r9ac0nb5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o51dot6hb"/><path class="ybcmecbwb"/><path class="r9ac0nb5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sprout-48" {...props}></Icon>
