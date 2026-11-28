<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihbrj940g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihbrj940g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:stethoscope-check" {...props}></Icon>
