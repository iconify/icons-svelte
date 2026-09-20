<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uev4s6r_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uev4s6r_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:united-nations" {...props}></Icon>
