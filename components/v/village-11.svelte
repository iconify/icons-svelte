<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7jj56biu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="d7jj56biu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:village-11" {...props}></Icon>
