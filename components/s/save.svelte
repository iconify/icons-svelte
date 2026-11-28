<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cui-ix3kn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cui-ix3kn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:save" {...props}></Icon>
