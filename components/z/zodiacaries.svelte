<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg8bt8bjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="gg8bt8bjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:zodiacaries" {...props}></Icon>
