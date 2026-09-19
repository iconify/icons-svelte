<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtj73wbon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="vtj73wbon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:security-group" {...props}></Icon>
