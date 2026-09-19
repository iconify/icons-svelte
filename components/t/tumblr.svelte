<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp9dpbnat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cp9dpbnat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:tumblr" {...props}></Icon>
