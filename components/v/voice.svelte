<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9wtobbqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="w9wtobbqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:voice" {...props}></Icon>
