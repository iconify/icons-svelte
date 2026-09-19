<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/laukk-9tg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="laukk-9tg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:shapes" {...props}></Icon>
