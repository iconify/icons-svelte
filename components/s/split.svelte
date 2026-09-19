<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b04q-pbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1023};
const content = `<path class="b04q-pbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:split" {...props}></Icon>
