<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2oc4mbya.css';
import '../../css/y/ye2ymf1gu.css';
import '../../css/t/tu7ylzb3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f2oc4mbya"/><path class="ye2ymf1gu"/><path class="tu7ylzb3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:siyuan" {...props}></Icon>
