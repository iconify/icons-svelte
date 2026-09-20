<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnj_f4vdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hnj_f4vdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:wind-turbine" {...props}></Icon>
