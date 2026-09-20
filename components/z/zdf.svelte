<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7czz_6xp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r7czz_6xp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:zdf" {...props}></Icon>
