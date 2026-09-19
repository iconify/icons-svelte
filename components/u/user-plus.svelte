<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6we54yhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j6we54yhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:user-plus" {...props}></Icon>
