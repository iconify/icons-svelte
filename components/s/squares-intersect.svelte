<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s96xmwb-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s96xmwb-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:squares-intersect" {...props}></Icon>
