<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia0t11r-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ia0t11r-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:triangle-solid-up-12" {...props}></Icon>
