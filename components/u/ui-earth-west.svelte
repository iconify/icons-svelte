<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e32cefbaq.css';
import '../../css/o/os3k17bny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="e32cefbaq"/><path class="os3k17bny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="geo:ui-earth-west" {...props}></Icon>
