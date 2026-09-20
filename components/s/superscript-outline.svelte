<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcn5xpbvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tcn5xpbvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:superscript-outline" {...props}></Icon>
