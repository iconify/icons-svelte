<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/htao7sagh.css';
import '../../css/u/uka4prbuv.css';
import '../../css/n/nvlvqpbyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="htao7sagh"/><path class="uka4prbuv"/><path class="nvlvqpbyf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tennis-ball-bold" {...props}></Icon>
