<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g34r42blo.css';
import '../../css/c/czru7nb1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g34r42blo"/><path class="czru7nb1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:sync-settings" {...props}></Icon>
