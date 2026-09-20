<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mji2cccso.css';
import '../../css/q/q2jwsje5o.css';
import '../../css/x/x1yme9bxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mji2cccso"/><path class="q2jwsje5o"/><path class="x1yme9bxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:signal" {...props}></Icon>
