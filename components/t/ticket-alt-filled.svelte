<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1q3vjbtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1q3vjbtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:ticket-alt-filled" {...props}></Icon>
