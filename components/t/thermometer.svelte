<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-fqx2gsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="s-fqx2gsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:thermometer" {...props}></Icon>
