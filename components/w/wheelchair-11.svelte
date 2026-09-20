<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9z8k-zja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="v9z8k-zja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:wheelchair-11" {...props}></Icon>
