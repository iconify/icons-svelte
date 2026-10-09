<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcda5wmtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vcda5wmtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:signal-none-20" {...props}></Icon>
