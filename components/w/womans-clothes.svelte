<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v35oqbc4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v35oqbc4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:womans-clothes" {...props}></Icon>
