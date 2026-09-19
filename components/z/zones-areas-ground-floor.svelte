<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_o_yvwyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v_o_yvwyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:zones-areas-ground-floor" {...props}></Icon>
