<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amj8daclg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="amj8daclg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:width" {...props}></Icon>
