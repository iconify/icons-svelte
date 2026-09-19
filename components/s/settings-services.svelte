<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_06tclpl.css';
import '../../css/z/z2y88ibfp.css';
import '../../css/g/govmrcrfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p_06tclpl"/><path class="z2y88ibfp"/><path class="govmrcrfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:settings-services" {...props}></Icon>
