<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpfk69-0z.css';
import '../../css/f/fnee-c65g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="rpfk69-0z"/><path class="fnee-c65g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:wheelchair" {...props}></Icon>
