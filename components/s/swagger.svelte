<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihq3wwgfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ihq3wwgfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:swagger" {...props}></Icon>
