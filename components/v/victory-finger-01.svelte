<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5pt9r29x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h5pt9r29x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:victory-finger-01" {...props}></Icon>
