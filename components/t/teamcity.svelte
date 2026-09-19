<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrz_pqblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="rrz_pqblx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:teamcity" {...props}></Icon>
