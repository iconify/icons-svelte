<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn-z210wd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yn-z210wd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:scanner-remix" {...props}></Icon>
