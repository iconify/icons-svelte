<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agefw_bcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="agefw_bcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:starship" {...props}></Icon>
