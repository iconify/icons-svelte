<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wddu7jbzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wddu7jbzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:seelf-dark" {...props}></Icon>
