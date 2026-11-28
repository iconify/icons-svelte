<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atm5b0wqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="atm5b0wqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:whistle-bold" {...props}></Icon>
