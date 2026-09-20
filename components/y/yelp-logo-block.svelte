<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wa422ab5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wa422ab5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:yelp-logo-block" {...props}></Icon>
