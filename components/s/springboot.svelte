<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya06mob_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ya06mob_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:springboot" {...props}></Icon>
