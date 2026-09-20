<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4b4zab6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="k4b4zab6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:search-category-solid" {...props}></Icon>
