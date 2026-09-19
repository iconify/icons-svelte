<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe6w1b_gw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fe6w1b_gw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:small-fan" {...props}></Icon>
