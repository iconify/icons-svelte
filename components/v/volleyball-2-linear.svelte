<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi41mr-8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hi41mr-8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:volleyball-2-linear" {...props}></Icon>
