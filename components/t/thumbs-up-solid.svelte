<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqiqw2bsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jqiqw2bsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:thumbs-up-solid" {...props}></Icon>
