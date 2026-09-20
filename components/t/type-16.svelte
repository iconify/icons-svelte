<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbf53ukmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gbf53ukmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:type-16" {...props}></Icon>
