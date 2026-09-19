<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd7v1qbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wd7v1qbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:sparkles" {...props}></Icon>
