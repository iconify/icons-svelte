<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijb5hobhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ijb5hobhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:text-vertical-alignment" {...props}></Icon>
