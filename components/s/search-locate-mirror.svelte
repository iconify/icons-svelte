<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajy8mmfuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ajy8mmfuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:search-locate-mirror" {...props}></Icon>
