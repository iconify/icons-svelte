<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2g5uz83b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n2g5uz83b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:stretching" {...props}></Icon>
