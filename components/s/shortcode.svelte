<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we21v81ge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="we21v81ge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:shortcode" {...props}></Icon>
