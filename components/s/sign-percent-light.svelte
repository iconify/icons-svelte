<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/a/a0zl88bqz.css';
import '../../css/f/f7o5wcbyu.css';
import '../../css/c/ccb59bcuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="a0zl88bqz"/><circle class="f7o5wcbyu"/><path class="ccb59bcuz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-percent-light" {...props}></Icon>
