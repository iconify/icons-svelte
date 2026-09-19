<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muu80cxvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="muu80cxvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:view-columns-20-solid" {...props}></Icon>
