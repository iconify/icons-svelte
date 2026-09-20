<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhbsr1bcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bhbsr1bcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:square-full" {...props}></Icon>
