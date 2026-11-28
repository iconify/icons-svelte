<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t55a15lpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t55a15lpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:washing-machine-clock" {...props}></Icon>
