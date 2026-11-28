<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyqqidb2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oyqqidb2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:smartwatch-heart" {...props}></Icon>
