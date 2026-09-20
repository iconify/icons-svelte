<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly7o7ggfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ly7o7ggfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:share-time-remix" {...props}></Icon>
