<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de_bqeb-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="de_bqeb-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="geo:turf-merge" {...props}></Icon>
