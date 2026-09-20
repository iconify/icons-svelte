<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/laiykvrmt.css';
import '../../css/g/gqsxbnbla.css';
import '../../css/s/swauynb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="laiykvrmt"/><path class="gqsxbnbla"/><path class="swauynb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:visualbasic" {...props}></Icon>
