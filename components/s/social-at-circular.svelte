<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd008e67m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dd008e67m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:social-at-circular" {...props}></Icon>
