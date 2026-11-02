<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko5dwac9v.css';
import '../../css/q/q_5fvp18n.css';
import '../../css/q/qua1n-5tb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ko5dwac9v"/><path class="q_5fvp18n"/><path class="qua1n-5tb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:vlang" {...props}></Icon>
