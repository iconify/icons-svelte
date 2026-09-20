<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7hdrzavt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7hdrzavt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:wave-triangle" {...props}></Icon>
