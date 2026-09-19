<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igo33jmrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="igo33jmrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:sorting-down" {...props}></Icon>
