<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3_m4jflw.css';
import '../../css/a/aaznl0b5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c3_m4jflw"/><path class="aaznl0b5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:vue-solid" {...props}></Icon>
