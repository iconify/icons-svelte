<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6xxkcbxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4.5,"top":-2};
const content = `<path class="s6xxkcbxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:yelp" {...props}></Icon>
