<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te427ubvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="te427ubvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:send-check" {...props}></Icon>
