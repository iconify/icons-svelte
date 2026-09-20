<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/leypshb3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="leypshb3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:star-solid" {...props}></Icon>
