<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv88c2lwy.css';
import '../../css/e/ezwpo0b0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nv88c2lwy"/><path class="ezwpo0b0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:vegetation-encroachment" {...props}></Icon>
