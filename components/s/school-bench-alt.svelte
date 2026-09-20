<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqhi0svru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="gqhi0svru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:school-bench-alt" {...props}></Icon>
