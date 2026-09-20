<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qto03pbfn.css';
import '../../css/h/hemx3sbcg.css';
import '../../css/d/dk02ivbjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qto03pbfn"/><path clip-rule="evenodd" class="hemx3sbcg"/><path class="dk02ivbjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:zone" {...props}></Icon>
