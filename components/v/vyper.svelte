<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fonvkfb5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fonvkfb5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:vyper" {...props}></Icon>
