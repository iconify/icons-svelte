<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7ounnd_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":666,"height":680};
const content = `<path class="a7ounnd_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:rss" {...props}></Icon>
