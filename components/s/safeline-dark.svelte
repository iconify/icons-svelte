<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc71osx1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lc71osx1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:safeline-dark" {...props}></Icon>
