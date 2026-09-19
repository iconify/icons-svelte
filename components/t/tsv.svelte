<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je3uw7zuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="je3uw7zuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:tsv" {...props}></Icon>
