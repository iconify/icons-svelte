<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfxlig6jj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dfxlig6jj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:walk-fill" {...props}></Icon>
