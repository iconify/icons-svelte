<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tch5idbxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tch5idbxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:volume-level-high-remix" {...props}></Icon>
