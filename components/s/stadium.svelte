<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke938i2kg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ke938i2kg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:stadium" {...props}></Icon>
