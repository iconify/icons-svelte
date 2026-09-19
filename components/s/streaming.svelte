<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x72w22bvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="x72w22bvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:streaming" {...props}></Icon>
