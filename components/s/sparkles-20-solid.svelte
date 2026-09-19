<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg5y5bc5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fg5y5bc5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:sparkles-20-solid" {...props}></Icon>
