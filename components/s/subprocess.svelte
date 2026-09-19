<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsza6i97b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nsza6i97b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:subprocess" {...props}></Icon>
