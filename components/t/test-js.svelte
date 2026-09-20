<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/voldqwefv.css';
import '../../css/z/z-xry-ugs.css';
import '../../css/d/d4viujbxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="voldqwefv"/><circle class="z-xry-ugs"/><path class="d4viujbxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:test-js" {...props}></Icon>
