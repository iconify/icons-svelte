<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njt32-bik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="njt32-bik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:soft-ice-cream" {...props}></Icon>
