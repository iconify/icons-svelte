<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yszp-9b8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yszp-9b8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sandstorm-20-bold" {...props}></Icon>
