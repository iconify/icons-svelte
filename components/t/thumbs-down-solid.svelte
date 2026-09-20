<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzx-n9bww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dzx-n9bww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:thumbs-down-solid" {...props}></Icon>
