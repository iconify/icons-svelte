<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pys6-7xbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pys6-7xbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:tag-fill" {...props}></Icon>
