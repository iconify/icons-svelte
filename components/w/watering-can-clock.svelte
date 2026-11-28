<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4xs89buj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j4xs89buj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:watering-can-clock" {...props}></Icon>
