<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqynkgb3j.css';
import '../../css/h/h2dipzbbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fqynkgb3j"/><path class="h2dipzbbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:zoom-out-16" {...props}></Icon>
