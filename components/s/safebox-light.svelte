<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axj7nzn7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="axj7nzn7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:safebox-light" {...props}></Icon>
