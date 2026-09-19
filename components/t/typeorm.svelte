<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kiwqdl9ga.css';
import '../../css/g/gkmrzoxxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="kiwqdl9ga"/><path class="gkmrzoxxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:typeorm" {...props}></Icon>
