<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/teeupqbdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="teeupqbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:virgin-media" {...props}></Icon>
