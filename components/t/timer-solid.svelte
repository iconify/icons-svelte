<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2qapdb-t.css';
import '../../css/q/qdsfr5okm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2qapdb-t"/><path clip-rule="evenodd" class="qdsfr5okm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:timer-solid" {...props}></Icon>
