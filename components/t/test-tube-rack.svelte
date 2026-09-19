<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl11e_b6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zl11e_b6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:test-tube-rack" {...props}></Icon>
