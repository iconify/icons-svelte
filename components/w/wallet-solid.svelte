<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9qlumbau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b9qlumbau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:wallet-solid" {...props}></Icon>
