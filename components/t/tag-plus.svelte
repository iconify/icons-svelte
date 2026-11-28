<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r49p3zgbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r49p3zgbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:tag-plus" {...props}></Icon>
