<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixivpjgka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ixivpjgka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:vote-yea" {...props}></Icon>
