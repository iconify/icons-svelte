<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsr72_20l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="vsr72_20l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:split" {...props}></Icon>
