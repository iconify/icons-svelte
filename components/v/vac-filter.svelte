<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anrso3m5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="anrso3m5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:vac-filter" {...props}></Icon>
