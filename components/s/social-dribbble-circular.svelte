<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b68-_jb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b68-_jb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:social-dribbble-circular" {...props}></Icon>
