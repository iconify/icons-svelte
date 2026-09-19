<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wezzffb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wezzffb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:sun-filled" {...props}></Icon>
