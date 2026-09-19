<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi8_oub_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="mi8_oub_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:user-warning" {...props}></Icon>
