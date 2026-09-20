<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0a42v_3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a0a42v_3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:traffic-left-right" {...props}></Icon>
