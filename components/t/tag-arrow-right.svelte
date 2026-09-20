<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7xu0wb0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n7xu0wb0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tag-arrow-right" {...props}></Icon>
