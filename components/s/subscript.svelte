<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s002xqn7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s002xqn7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:subscript" {...props}></Icon>
