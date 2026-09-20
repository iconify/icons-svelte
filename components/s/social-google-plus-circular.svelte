<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfb1-up3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfb1-up3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:social-google-plus-circular" {...props}></Icon>
