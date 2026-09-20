<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy0u6tb9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oy0u6tb9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:treyarch" {...props}></Icon>
