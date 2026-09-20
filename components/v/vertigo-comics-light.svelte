<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7m_-rsmc.css';
import '../../css/n/n5um080gu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g7m_-rsmc"/><path class="n5um080gu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vertigo-comics-light" {...props}></Icon>
