<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4rw3-bda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4rw3-bda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shop-plus" {...props}></Icon>
