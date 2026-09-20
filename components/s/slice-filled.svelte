<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldll2qu4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ldll2qu4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:slice-filled" {...props}></Icon>
