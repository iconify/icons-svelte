<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhd17n_ca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jhd17n_ca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:text-short-paragraph" {...props}></Icon>
