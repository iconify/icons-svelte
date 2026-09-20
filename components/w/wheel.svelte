<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1b1l1b9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p1b1l1b9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:wheel" {...props}></Icon>
