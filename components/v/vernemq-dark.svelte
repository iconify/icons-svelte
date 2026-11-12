<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-bs936qw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u-bs936qw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vernemq-dark" {...props}></Icon>
