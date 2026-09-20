<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb-ftubup.css';
import '../../css/e/e3bbx6bvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kb-ftubup"/><path clip-rule="evenodd" class="e3bbx6bvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:search-property-solid" {...props}></Icon>
