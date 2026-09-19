<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6yd7cbna.css';
import '../../css/x/xxps6nbqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w6yd7cbna"/><path class="xxps6nbqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:station" {...props}></Icon>
