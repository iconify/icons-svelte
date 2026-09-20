<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb918ob3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zb918ob3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:sort-desc-filled" {...props}></Icon>
