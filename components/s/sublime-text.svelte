<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5foiccuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k5foiccuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:sublime-text" {...props}></Icon>
