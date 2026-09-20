<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/majb9u9sn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="majb9u9sn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:table-large-plus" {...props}></Icon>
