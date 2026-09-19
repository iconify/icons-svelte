<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7020zbci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":528,"height":448};
const content = `<path class="d7020zbci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:water-temperature-50" {...props}></Icon>
