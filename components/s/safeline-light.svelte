<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzthh7bet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kzthh7bet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:safeline-light" {...props}></Icon>
