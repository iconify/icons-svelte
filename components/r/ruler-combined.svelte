<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-cdyfb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-cdyfb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:ruler-combined" {...props}></Icon>
