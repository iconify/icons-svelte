<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1euwac9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="f1euwac9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:timer" {...props}></Icon>
