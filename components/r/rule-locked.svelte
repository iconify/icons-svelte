<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng-8hw7il.css';
import '../../css/p/p38-woblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ng-8hw7il"/><path class="p38-woblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:rule-locked" {...props}></Icon>
