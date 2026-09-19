<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahxe6_p3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ahxe6_p3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:text-bubble-fill" {...props}></Icon>
