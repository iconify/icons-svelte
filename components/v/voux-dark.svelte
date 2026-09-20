<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-p29-bxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k-p29-bxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:voux-dark" {...props}></Icon>
