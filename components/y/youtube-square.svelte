<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_ulcowzu.css';
import '../../css/e/en0k_qb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f_ulcowzu"/><path class="en0k_qb_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:youtube-square" {...props}></Icon>
