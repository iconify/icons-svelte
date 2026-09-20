<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dihyg454b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dihyg454b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:searchapi" {...props}></Icon>
