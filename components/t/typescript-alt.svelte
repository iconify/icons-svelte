<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itclvu5is.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="itclvu5is"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:typescript-alt" {...props}></Icon>
