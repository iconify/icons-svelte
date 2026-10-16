<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqpralk8i.css';
import '../../css/r/rfhud25gy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bqpralk8i"/><path class="rfhud25gy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tower-section-20" {...props}></Icon>
