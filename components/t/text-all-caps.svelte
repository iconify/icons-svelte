<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f26vo10au.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f26vo10au"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:text-all-caps" {...props}></Icon>
