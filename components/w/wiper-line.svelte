<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs6abtbab.css';
import '../../css/y/y0euu7b0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cs6abtbab"/><path class="y0euu7b0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wiper-line" {...props}></Icon>
