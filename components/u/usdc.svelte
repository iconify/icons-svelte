<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdr4ynbph.css';
import '../../css/y/y-mhm093y.css';
import '../../css/v/v286mkswn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2000,"height":2000};
const content = `<path class="qdr4ynbph"/><path class="y-mhm093y"/><path class="v286mkswn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:usdc" {...props}></Icon>
