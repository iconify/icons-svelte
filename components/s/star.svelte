<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ne3uqob6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="ne3uqob6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:star" {...props}></Icon>
