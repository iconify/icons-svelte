<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3u6ksb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o3u6ksb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:satellite-dish" {...props}></Icon>
