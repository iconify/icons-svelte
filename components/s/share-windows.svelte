<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_tiv4jgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g_tiv4jgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:share-windows" {...props}></Icon>
