<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea3l3ebac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1568,"height":1280};
const content = `<path class="ea3l3ebac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:sign-out" {...props}></Icon>
