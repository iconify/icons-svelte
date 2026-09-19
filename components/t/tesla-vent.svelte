<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtrjnpbcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qtrjnpbcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:tesla-vent" {...props}></Icon>
