<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2n529b7c.css';
import '../../css/d/d363y7bqh.css';
import '../../css/g/gtfd-mlws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j2n529b7c"/><path class="d363y7bqh"/><path class="gtfd-mlws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wineglass-bold-duotone" {...props}></Icon>
