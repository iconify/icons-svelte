<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwimcqx0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kwimcqx0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:trophy-filled" {...props}></Icon>
