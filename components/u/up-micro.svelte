<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9qz21bzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":471,"height":1000};
const content = `<path class="c9qz21bzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:up-micro" {...props}></Icon>
