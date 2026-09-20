<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_snteb-s.css';
import '../../css/b/b05e0yo7m.css';
import '../../css/t/tnas7_1ty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":33};
const content = `<path clip-rule="evenodd" class="b_snteb-s"/><path clip-rule="evenodd" class="b05e0yo7m"/><path clip-rule="evenodd" class="tnas7_1ty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:vis-builder" {...props}></Icon>
