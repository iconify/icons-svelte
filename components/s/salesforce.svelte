<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttdah_b7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ttdah_b7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:salesforce" {...props}></Icon>
