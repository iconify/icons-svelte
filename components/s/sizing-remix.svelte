<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nuiwu0b0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nuiwu0b0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:sizing-remix" {...props}></Icon>
