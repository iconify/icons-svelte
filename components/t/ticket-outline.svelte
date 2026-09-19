<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pfvmrrbrb.css';
import '../../css/f/fnh1hbb7b.css';
import '../../css/f/f1ot_mbyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ticket-outline"><g class="Vector cuyn6tgcc"><path clip-rule="evenodd" class="pfvmrrbrb"/><path clip-rule="evenodd" class="fnh1hbb7b"/><path class="f1ot_mbyf"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:ticket-outline" {...props}></Icon>
