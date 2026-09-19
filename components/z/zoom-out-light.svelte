<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9yegzbrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m9yegzbrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:zoom-out-light" {...props}></Icon>
