<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad3rgxbvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ad3rgxbvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:wealth-1-filled" {...props}></Icon>
