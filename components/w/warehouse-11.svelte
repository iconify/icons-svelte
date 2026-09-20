<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhyjuybmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="mhyjuybmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:warehouse-11" {...props}></Icon>
