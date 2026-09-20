<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aii-ix-wu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aii-ix-wu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sticker-square-outline" {...props}></Icon>
