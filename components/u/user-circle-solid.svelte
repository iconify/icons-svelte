<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsatub3fk.css';
import '../../css/c/c2aqpmbiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dsatub3fk"/><path clip-rule="evenodd" class="c2aqpmbiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:user-circle-solid" {...props}></Icon>
