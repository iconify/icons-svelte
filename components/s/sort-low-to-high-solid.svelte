<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1s84rbss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="r1s84rbss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:sort-low-to-high-solid" {...props}></Icon>
