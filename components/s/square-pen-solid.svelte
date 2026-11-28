<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ennbw5bqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ennbw5bqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-pen-solid" {...props}></Icon>
