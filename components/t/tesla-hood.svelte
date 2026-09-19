<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzshn-b3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzshn-b3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:tesla-hood" {...props}></Icon>
