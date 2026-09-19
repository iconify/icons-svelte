<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lov-w_bok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lov-w_bok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:test-typescript" {...props}></Icon>
