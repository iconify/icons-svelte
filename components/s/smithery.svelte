<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lenqjybbl.css';
import '../../css/s/sizgdyb9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lenqjybbl"/><path class="sizgdyb9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:smithery" {...props}></Icon>
