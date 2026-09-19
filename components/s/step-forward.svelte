<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2umil-pm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="i2umil-pm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:step-forward" {...props}></Icon>
