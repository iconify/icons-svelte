<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ioxie2bbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ioxie2bbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:ruler-remix" {...props}></Icon>
