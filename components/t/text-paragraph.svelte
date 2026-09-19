<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8uf4nboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e8uf4nboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:text-paragraph" {...props}></Icon>
