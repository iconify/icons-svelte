<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1k5fg00x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="v1k5fg00x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:sandstorm" {...props}></Icon>
