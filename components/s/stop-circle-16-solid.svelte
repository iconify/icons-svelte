<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3aqexy4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b3aqexy4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:stop-circle-16-solid" {...props}></Icon>
