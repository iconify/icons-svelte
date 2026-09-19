<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gum-icegm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="gum-icegm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:speech-balloon-small-filled" {...props}></Icon>
