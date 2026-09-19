<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od5_hmb1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="od5_hmb1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:telephone-minus-fill" {...props}></Icon>
