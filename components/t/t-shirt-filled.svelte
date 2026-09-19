<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz_d1jkgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jz_d1jkgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:t-shirt-filled" {...props}></Icon>
