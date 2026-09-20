<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csv4lubho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="csv4lubho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:social-flickr-circular" {...props}></Icon>
