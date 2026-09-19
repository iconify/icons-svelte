<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf9byy3ul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="tf9byy3ul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:waving-hand" {...props}></Icon>
