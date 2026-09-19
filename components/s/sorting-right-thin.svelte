<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnf3cs2wa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnf3cs2wa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sorting-right-thin" {...props}></Icon>
