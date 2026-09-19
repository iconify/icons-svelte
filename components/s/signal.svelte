<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei16dbcaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ei16dbcaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:signal" {...props}></Icon>
