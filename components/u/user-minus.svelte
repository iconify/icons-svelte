<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6g48wlqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j6g48wlqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:user-minus" {...props}></Icon>
