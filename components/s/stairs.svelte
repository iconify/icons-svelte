<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz8qy3bgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":63,"height":64};
const content = `<path class="kz8qy3bgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:stairs" {...props}></Icon>
