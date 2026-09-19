<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ondal-58d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ondal-58d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:xing" {...props}></Icon>
