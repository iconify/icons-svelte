<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuqu2b3jw.css';
import '../../css/u/uxzknvoyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="yuqu2b3jw"/><path clip-rule="evenodd" class="uxzknvoyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:targon" {...props}></Icon>
