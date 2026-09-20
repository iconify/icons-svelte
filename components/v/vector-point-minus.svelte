<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o19s5kgey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o19s5kgey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vector-point-minus" {...props}></Icon>
