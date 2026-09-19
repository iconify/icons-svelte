<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8al6yiie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o8al6yiie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:tsx-alt" {...props}></Icon>
