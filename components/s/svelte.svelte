<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdhb-7r4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":426,"height":512};
const content = `<path class="pdhb-7r4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:svelte" {...props}></Icon>
