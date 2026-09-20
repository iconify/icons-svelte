<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff-xl2bud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ff-xl2bud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:window-1-filled" {...props}></Icon>
