<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-mwivb5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p-mwivb5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:trend-down-fill" {...props}></Icon>
