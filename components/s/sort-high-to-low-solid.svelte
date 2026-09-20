<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh-4jo2tm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="gh-4jo2tm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:sort-high-to-low-solid" {...props}></Icon>
