<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh5fhcc4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="gh5fhcc4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:wakatime" {...props}></Icon>
