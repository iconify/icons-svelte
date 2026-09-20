<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igpenwb0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="igpenwb0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:xwiki-light" {...props}></Icon>
