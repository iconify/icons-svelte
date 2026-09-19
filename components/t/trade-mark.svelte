<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlk0frbgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zlk0frbgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:trade-mark" {...props}></Icon>
