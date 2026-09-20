<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oya1jhbbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oya1jhbbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:token-null" {...props}></Icon>
