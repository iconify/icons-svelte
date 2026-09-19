<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9uz-ybvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="r9uz-ybvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:selector" {...props}></Icon>
