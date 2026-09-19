<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyhlb4b3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":528,"height":448};
const content = `<path class="hyhlb4b3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:water-temperature-70" {...props}></Icon>
