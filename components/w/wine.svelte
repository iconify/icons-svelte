<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2_fs0idi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":23,"height":32};
const content = `<path class="y2_fs0idi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:wine" {...props}></Icon>
