<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz7yqsbfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vz7yqsbfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:slack-stroke-16" {...props}></Icon>
