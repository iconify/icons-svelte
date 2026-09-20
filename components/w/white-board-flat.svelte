<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/g/g_mc4skjc.css';
import '../../css/b/b3bqa4bnf.css';
import '../../css/e/erxplv5qz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="g_mc4skjc"/><path class="b3bqa4bnf"/><path class="erxplv5qz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:white-board-flat" {...props}></Icon>
