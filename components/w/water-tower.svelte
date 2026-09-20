<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eaz2klblv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="eaz2klblv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:water-tower" {...props}></Icon>
