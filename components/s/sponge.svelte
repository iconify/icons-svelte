<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua9lbocea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ua9lbocea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:sponge" {...props}></Icon>
