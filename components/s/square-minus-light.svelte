<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idssa5b9o.css';
import '../../css/r/rb33ccc5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="idssa5b9o"/><path class="rb33ccc5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:square-minus-light" {...props}></Icon>
