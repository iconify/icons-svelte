<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-abih8ua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-abih8ua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sr-radio" {...props}></Icon>
