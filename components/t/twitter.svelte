<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id30-xb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="id30-xb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:twitter" {...props}></Icon>
