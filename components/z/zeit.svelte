<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amxju2bxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="amxju2bxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:zeit" {...props}></Icon>
