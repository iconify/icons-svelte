<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2-48nb5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f2-48nb5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:shield-check-sharp-fill" {...props}></Icon>
