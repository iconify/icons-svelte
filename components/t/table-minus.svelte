<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qap4ejbsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qap4ejbsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:table-minus" {...props}></Icon>
