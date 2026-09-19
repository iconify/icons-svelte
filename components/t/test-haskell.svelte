<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wigy65mwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wigy65mwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:test-haskell" {...props}></Icon>
