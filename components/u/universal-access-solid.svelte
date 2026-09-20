<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n78-1ulvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n78-1ulvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:universal-access-solid" {...props}></Icon>
