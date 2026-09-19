<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpk-spksa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jpk-spksa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:slash-16-solid" {...props}></Icon>
