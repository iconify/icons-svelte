<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmj5g9btx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="lmj5g9btx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:view-file" {...props}></Icon>
