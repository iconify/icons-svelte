<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0_n4gb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l0_n4gb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:spa-remix" {...props}></Icon>
