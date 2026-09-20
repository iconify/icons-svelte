<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wiw_s6b9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wiw_s6b9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:ruby-outline" {...props}></Icon>
