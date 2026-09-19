<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb1m19bkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qb1m19bkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:syringe" {...props}></Icon>
