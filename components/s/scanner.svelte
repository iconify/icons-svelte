<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7y63b7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="sv7y63b7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:scanner" {...props}></Icon>
