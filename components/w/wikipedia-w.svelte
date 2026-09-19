<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v79c05byr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="v79c05byr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:wikipedia-w" {...props}></Icon>
