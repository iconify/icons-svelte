<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui5hz-rai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ui5hz-rai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:ship-filled" {...props}></Icon>
