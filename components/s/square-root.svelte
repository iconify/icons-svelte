<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8ah_44wd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="t8ah_44wd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:square-root" {...props}></Icon>
