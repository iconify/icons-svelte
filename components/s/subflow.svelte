<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrmf1gb-i.css';
import '../../css/s/sf1cmcczv.css';
import '../../css/q/q0i1j3b0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hrmf1gb-i"/><path class="sf1cmcczv"/><path class="q0i1j3b0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:subflow" {...props}></Icon>
