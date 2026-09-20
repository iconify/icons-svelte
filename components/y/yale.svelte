<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtax9pb3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xtax9pb3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:yale" {...props}></Icon>
