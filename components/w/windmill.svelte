<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6h2r6bje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="t6h2r6bje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:windmill" {...props}></Icon>
