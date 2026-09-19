<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akta-9j2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="akta-9j2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:view-2d" {...props}></Icon>
