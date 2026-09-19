<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uacxlzfww.css';
import '../../css/j/j0vie5bjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uacxlzfww"/><path clip-rule="evenodd" class="j0vie5bjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:visible-filled" {...props}></Icon>
