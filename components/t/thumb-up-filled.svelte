<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9re83ueq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x9re83ueq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:thumb-up-filled" {...props}></Icon>
