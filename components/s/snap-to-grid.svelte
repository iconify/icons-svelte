<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq41pieit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qq41pieit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:snap-to-grid" {...props}></Icon>
