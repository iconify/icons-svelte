<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tas1uj8qs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tas1uj8qs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:scan-heart-solid" {...props}></Icon>
