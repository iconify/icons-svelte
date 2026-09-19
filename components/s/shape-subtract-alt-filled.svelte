<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lodgmg-3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lodgmg-3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shape-subtract-alt-filled" {...props}></Icon>
