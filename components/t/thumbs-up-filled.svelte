<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twtng14ab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="twtng14ab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:thumbs-up-filled" {...props}></Icon>
