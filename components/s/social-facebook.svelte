<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbdjjj2ra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbdjjj2ra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:social-facebook" {...props}></Icon>
