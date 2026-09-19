<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu1o-cjme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="cu1o-cjme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-hi5" {...props}></Icon>
