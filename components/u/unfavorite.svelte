<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgv87b72c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="rgv87b72c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:unfavorite" {...props}></Icon>
