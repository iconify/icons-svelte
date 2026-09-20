<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn0_anb_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fn0_anb_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:skip-minus" {...props}></Icon>
