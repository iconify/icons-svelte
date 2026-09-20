<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3kiame8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d3kiame8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:video" {...props}></Icon>
