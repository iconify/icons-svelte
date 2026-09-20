<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqe1w2mmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wqe1w2mmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:text-bar-remix" {...props}></Icon>
