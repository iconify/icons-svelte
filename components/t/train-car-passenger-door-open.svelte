<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fykkjg8af.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fykkjg8af"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:train-car-passenger-door-open" {...props}></Icon>
