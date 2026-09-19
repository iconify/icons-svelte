<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za8lh3llf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="za8lh3llf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:train" {...props}></Icon>
