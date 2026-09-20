<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/paghlm9jp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="paghlm9jp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:unlock-circle-outline" {...props}></Icon>
