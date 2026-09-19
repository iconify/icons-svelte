<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzdgy0vkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tzdgy0vkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:trending-up-fill" {...props}></Icon>
