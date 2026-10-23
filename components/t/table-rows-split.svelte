<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6c4trb0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6c4trb0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:table-rows-split" {...props}></Icon>
