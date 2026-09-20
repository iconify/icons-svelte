<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b05s4wdea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b05s4wdea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vector-square-minus" {...props}></Icon>
