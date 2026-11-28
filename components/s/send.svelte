<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w974s6-xe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w974s6-xe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:send" {...props}></Icon>
