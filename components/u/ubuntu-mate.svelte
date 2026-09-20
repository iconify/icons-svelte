<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynwtrqblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ynwtrqblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ubuntu-mate" {...props}></Icon>
