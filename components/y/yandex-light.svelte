<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kctpacchs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kctpacchs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yandex-light" {...props}></Icon>
