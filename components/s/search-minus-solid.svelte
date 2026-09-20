<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1liidc4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t1liidc4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:search-minus-solid" {...props}></Icon>
