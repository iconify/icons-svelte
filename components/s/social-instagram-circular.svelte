<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1f-g4bho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1f-g4bho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:social-instagram-circular" {...props}></Icon>
