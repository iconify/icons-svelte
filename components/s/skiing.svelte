<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm4c8-w_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nm4c8-w_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:skiing" {...props}></Icon>
