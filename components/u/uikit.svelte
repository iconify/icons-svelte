<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj7k5cndy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aj7k5cndy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:uikit" {...props}></Icon>
