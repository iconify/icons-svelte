<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfi7subhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gfi7subhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:woodpecker" {...props}></Icon>
