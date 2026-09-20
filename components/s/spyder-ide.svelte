<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox5awiots.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ox5awiots"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:spyder-ide" {...props}></Icon>
