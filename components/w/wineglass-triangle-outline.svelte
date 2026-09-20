<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/craa3rrjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="craa3rrjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wineglass-triangle-outline" {...props}></Icon>
