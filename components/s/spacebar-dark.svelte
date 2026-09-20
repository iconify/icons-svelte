<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ix0d87bse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ix0d87bse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:spacebar-dark" {...props}></Icon>
