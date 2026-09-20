<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt0fh2bnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jt0fh2bnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sale-circle" {...props}></Icon>
