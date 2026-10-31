<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejzqbh7mz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ejzqbh7mz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:table-cells-split-16-solid" {...props}></Icon>
