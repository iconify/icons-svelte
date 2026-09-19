<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af13y3bim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="af13y3bim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:unfold-open" {...props}></Icon>
