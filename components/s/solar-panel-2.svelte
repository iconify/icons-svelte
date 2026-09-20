<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5intkb-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u5intkb-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:solar-panel-2" {...props}></Icon>
