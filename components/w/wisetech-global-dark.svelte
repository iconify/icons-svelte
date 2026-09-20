<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amc34abky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1534,"height":1534};
const content = `<path class="amc34abky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wisetech-global-dark" {...props}></Icon>
