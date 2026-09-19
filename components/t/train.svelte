<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s93in0bsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s93in0bsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:train" {...props}></Icon>
