<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik_gqmbru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":432};
const content = `<path class="ik_gqmbru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:share" {...props}></Icon>
