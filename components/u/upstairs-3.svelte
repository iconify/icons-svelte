<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iknyyxzct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iknyyxzct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:upstairs-3" {...props}></Icon>
