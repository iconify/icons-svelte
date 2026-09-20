<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n072rrlng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="n072rrlng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:text-strike-through" {...props}></Icon>
