<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whu9aebkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whu9aebkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:sort-alphabetically-outline" {...props}></Icon>
