<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n97kby4rh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n97kby4rh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:timer-check-filled" {...props}></Icon>
