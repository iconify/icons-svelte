<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo26x2-5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="wo26x2-5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:snow-capped-mountain" {...props}></Icon>
