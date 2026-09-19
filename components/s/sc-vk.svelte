<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7gvf4b-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path clip-rule="evenodd" class="t7gvf4b-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:sc-vk" {...props}></Icon>
