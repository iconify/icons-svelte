<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v82socb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="v82socb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:thermometer-exterior" {...props}></Icon>
