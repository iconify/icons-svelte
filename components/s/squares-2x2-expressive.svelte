<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbn-w6b2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dbn-w6b2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:squares-2x2-expressive" {...props}></Icon>
