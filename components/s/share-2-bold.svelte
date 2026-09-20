<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kujboibdf.css';
import '../../css/t/txm8quc0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kujboibdf"/><path class="txm8quc0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:share-2-bold" {...props}></Icon>
