<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1-6q3lmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1-6q3lmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:social-github-circular" {...props}></Icon>
