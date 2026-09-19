<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/va-kg5ifn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="va-kg5ifn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:zest" {...props}></Icon>
