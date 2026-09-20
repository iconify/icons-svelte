<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dx4lb5byr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dx4lb5byr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:xcode" {...props}></Icon>
