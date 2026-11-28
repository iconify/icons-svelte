<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mco8jmbei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mco8jmbei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:square" {...props}></Icon>
