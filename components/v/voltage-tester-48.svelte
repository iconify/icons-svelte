<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7445dbmo.css';
import '../../css/c/c9yqj13fx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g7445dbmo"/><path class="c9yqj13fx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:voltage-tester-48" {...props}></Icon>
