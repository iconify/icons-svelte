<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5gmf2d8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w5gmf2d8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:user-remove-solid" {...props}></Icon>
