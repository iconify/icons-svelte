<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd665b1nm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nd665b1nm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:slideshare" {...props}></Icon>
