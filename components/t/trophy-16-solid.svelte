<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr7uqc0zd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nr7uqc0zd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:trophy-16-solid" {...props}></Icon>
