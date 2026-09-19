<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k26wlw6el.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="k26wlw6el"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:video" {...props}></Icon>
