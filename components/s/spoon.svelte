<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuraqd2at.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kuraqd2at"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:spoon" {...props}></Icon>
