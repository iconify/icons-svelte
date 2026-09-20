<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icj2v8t5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="icj2v8t5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:triangle-stroked-15" {...props}></Icon>
