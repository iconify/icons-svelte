<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgb-6724v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tgb-6724v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:yelp" {...props}></Icon>
