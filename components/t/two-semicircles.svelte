<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/na-6mk1vc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="na-6mk1vc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:two-semicircles" {...props}></Icon>
