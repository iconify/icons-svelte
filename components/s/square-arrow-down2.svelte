<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr69i1bgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mr69i1bgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:square-arrow-down2" {...props}></Icon>
