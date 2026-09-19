<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srm-1uqad.css';
import '../../css/s/s6jqjmbla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="srm-1uqad"/><path class="s6jqjmbla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:scala" {...props}></Icon>
