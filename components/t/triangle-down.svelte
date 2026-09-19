<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sklii6bbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":240,"height":700};
const content = `<path class="sklii6bbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:triangle-down" {...props}></Icon>
