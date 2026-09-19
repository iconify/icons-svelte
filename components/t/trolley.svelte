<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzf8ydn4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zzf8ydn4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:trolley" {...props}></Icon>
