<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkr1zvh1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tkr1zvh1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:server-alert" {...props}></Icon>
