<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilf97_gpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="ilf97_gpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:vk" {...props}></Icon>
