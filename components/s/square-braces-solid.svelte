<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otok5pczo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="otok5pczo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-braces-solid" {...props}></Icon>
