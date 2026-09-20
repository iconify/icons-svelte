<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o43hwyblp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o43hwyblp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:storefront-check" {...props}></Icon>
