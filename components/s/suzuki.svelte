<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7bd_3icd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a7bd_3icd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:suzuki" {...props}></Icon>
