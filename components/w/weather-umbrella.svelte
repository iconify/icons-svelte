<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0kbq7sil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b0kbq7sil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:weather-umbrella" {...props}></Icon>
