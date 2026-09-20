<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhqjbnb1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhqjbnb1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:yelp" {...props}></Icon>
