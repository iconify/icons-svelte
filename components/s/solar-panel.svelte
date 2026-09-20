<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqo4ribfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cqo4ribfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:solar-panel" {...props}></Icon>
