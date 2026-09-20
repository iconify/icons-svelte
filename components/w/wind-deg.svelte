<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghyal0hqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="ghyal0hqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:wind-deg" {...props}></Icon>
