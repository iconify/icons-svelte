<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3lmd4bmk.css';
import '../../css/f/fvmh2ibcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f3lmd4bmk"/><path class="fvmh2ibcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:rule-draft" {...props}></Icon>
