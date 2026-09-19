<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnym00-jn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="rnym00-jn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:status-online" {...props}></Icon>
