<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt8z3m2uo.css';
import '../../css/r/r6ujjtbfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jt8z3m2uo"/><path class="r6ujjtbfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:warning-alt-inverted" {...props}></Icon>
