<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijr-y-b0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":896};
const content = `<path class="ijr-y-b0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:stiletto" {...props}></Icon>
