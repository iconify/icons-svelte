<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rctg5spaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rctg5spaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:signal-slash" {...props}></Icon>
