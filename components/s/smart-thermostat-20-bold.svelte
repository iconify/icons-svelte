<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0oa-qzdz.css';
import '../../css/i/iz38uxbae.css';
import '../../css/b/bzm25wbfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c0oa-qzdz"/><path class="iz38uxbae"/><path class="bzm25wbfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smart-thermostat-20-bold" {...props}></Icon>
