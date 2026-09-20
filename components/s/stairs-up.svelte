<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4n_5lbrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4n_5lbrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:stairs-up" {...props}></Icon>
