<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aik43r5pi.css';
import '../../css/d/dl12cln-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aik43r5pi"/><path class="dl12cln-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:task-settings" {...props}></Icon>
