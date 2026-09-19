<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apskv5bzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="apskv5bzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:suit-diamond-fill" {...props}></Icon>
