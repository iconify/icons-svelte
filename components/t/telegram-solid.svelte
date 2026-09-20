<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bz6nd9amy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bz6nd9amy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:telegram-solid" {...props}></Icon>
