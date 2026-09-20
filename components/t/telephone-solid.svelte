<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4_xnybpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s4_xnybpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:telephone-solid" {...props}></Icon>
