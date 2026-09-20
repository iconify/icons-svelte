<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnr7p1g2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dnr7p1g2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:search" {...props}></Icon>
