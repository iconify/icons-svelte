<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avxnjrb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="avxnjrb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:stumbleupon" {...props}></Icon>
