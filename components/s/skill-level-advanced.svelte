<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbgenzbat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qbgenzbat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:skill-level-advanced" {...props}></Icon>
