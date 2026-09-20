<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olmg6db3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="olmg6db3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:skeleton" {...props}></Icon>
