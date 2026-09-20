<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv-x43eqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zv-x43eqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:visible-remix" {...props}></Icon>
