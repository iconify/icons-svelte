<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7zrzpbzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r7zrzpbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:sailboat-fill" {...props}></Icon>
