<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5b2mrbie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d5b2mrbie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:scale" {...props}></Icon>
