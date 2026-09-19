<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzgw8sbmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="uzgw8sbmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:speech-balloon-empty" {...props}></Icon>
