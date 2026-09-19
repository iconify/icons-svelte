<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbwga7b8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pbwga7b8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:shopping-bag-16-solid" {...props}></Icon>
