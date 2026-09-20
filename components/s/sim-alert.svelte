<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vww7f4bcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vww7f4bcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:sim-alert" {...props}></Icon>
