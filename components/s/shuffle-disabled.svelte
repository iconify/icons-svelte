<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i60qu5ylv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i60qu5ylv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shuffle-disabled" {...props}></Icon>
