<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqvgs1b3g.css';
import '../../css/u/uiqysqbcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gqvgs1b3g"/><path class="uiqysqbcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:volume-20-bold" {...props}></Icon>
