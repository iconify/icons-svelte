<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ut3ipcchr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ut3ipcchr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:users-x" {...props}></Icon>
