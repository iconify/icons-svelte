<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aicakhbye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aicakhbye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:smartfox-light" {...props}></Icon>
