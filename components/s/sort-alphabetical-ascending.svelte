<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txe6li42a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="txe6li42a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sort-alphabetical-ascending" {...props}></Icon>
