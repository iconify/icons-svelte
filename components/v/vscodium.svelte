<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_d_m5bzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_d_m5bzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:vscodium" {...props}></Icon>
