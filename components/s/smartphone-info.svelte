<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c45dohe0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c45dohe0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:smartphone-info" {...props}></Icon>
