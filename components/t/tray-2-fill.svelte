<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cazy9sb6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="cazy9sb6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:tray-2-fill" {...props}></Icon>
