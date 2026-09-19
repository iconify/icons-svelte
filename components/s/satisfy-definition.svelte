<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecfa-38zj.css';
import '../../css/a/awir01b8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ecfa-38zj"/><path class="awir01b8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:satisfy-definition" {...props}></Icon>
