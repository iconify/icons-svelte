<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0oedhzqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0oedhzqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:shopping-bag-line" {...props}></Icon>
