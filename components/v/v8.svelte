<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/deekjd39l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="deekjd39l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:v8" {...props}></Icon>
