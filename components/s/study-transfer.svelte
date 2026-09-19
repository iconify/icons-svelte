<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq-zhfbfg.css';
import '../../css/d/did4e-x8k.css';
import '../../css/f/fbylp1beo.css';
import '../../css/v/v29e9xbrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sq-zhfbfg"/><path class="did4e-x8k"/><path class="fbylp1beo"/><path class="v29e9xbrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:study-transfer" {...props}></Icon>
