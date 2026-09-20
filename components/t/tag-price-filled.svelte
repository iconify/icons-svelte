<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt2k5rb9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mt2k5rb9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:tag-price-filled" {...props}></Icon>
