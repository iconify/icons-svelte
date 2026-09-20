<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si4f12egu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="si4f12egu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:sizing" {...props}></Icon>
