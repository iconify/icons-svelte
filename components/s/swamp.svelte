<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7a7_mvmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y7a7_mvmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:swamp" {...props}></Icon>
