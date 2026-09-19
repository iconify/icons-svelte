<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6cp9b5nx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v6cp9b5nx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:thumbs-up" {...props}></Icon>
