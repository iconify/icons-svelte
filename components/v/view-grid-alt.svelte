<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib3dfhbkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ib3dfhbkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:view-grid-alt" {...props}></Icon>
