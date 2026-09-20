<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jva7wh10t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jva7wh10t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:social-last-fm-circular" {...props}></Icon>
