<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1-_uqbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1-_uqbri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:telenor" {...props}></Icon>
