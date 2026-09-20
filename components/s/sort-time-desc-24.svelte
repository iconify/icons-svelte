<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f849z9lwr.css';
import '../../css/t/tii820b4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f849z9lwr"/><path clip-rule="evenodd" class="tii820b4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:sort-time-desc-24" {...props}></Icon>
