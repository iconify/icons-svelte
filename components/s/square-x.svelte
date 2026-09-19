<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eef02kbca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eef02kbca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:square-x" {...props}></Icon>
