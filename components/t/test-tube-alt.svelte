<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4sd0g1go.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":24};
const content = `<path class="k4sd0g1go"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:test-tube-alt" {...props}></Icon>
