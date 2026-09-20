<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhsu0ecwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uhsu0ecwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:sparkles-2" {...props}></Icon>
