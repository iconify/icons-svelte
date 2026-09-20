<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9finxy4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o9finxy4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:typewriter-remix" {...props}></Icon>
