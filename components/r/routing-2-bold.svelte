<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zeyv90bgs.css';
import '../../css/q/qrmgfrbnf.css';
import '../../css/p/peei90bcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zeyv90bgs"/><path class="qrmgfrbnf"/><path clip-rule="evenodd" class="peei90bcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:routing-2-bold" {...props}></Icon>
