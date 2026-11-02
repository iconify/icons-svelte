<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozh610-un.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ozh610-un"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-pin-line" {...props}></Icon>
