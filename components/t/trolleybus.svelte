<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k32cw6e7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k32cw6e7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:trolleybus" {...props}></Icon>
