<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijkhwubvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":999.978,"height":1000};
const content = `<path class="ijkhwubvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="brandico:skype" {...props}></Icon>
