<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjg6q_bph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":288,"height":384};
const content = `<path class="kjg6q_bph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:volume-down" {...props}></Icon>
