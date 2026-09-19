<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhp66mbcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bhp66mbcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sorting-left-fill" {...props}></Icon>
