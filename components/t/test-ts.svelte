<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_90onbxw.css';
import '../../css/l/l9oavwvjg.css';
import '../../css/s/sgkyoxxea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u_90onbxw"/><circle class="l9oavwvjg"/><path class="sgkyoxxea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:test-ts" {...props}></Icon>
