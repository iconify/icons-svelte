<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy_wbc1rc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="zy_wbc1rc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:web-template" {...props}></Icon>
