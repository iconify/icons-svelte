<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hk6jsc0yv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hk6jsc0yv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:tablet-outline" {...props}></Icon>
