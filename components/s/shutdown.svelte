<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_t-t1bub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_t-t1bub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:shutdown" {...props}></Icon>
