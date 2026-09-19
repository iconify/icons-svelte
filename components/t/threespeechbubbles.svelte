<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-4ziq31h.css';
import '../../css/o/o7-5ytbma.css';
import '../../css/n/n2e31kbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q-4ziq31h"/><path class="o7-5ytbma"/><path class="n2e31kbxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:threespeechbubbles" {...props}></Icon>
