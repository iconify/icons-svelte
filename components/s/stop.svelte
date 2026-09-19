<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ip-hiqobi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ip-hiqobi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:stop" {...props}></Icon>
