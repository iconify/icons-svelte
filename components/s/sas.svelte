<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9cgckbcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":342,"height":512};
const content = `<path class="v9cgckbcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:sas" {...props}></Icon>
