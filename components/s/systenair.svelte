<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ont9fwm1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ont9fwm1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:systenair" {...props}></Icon>
