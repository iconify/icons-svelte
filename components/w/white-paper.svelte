<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk0ivzbcg.css';
import '../../css/x/x22kdubov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tk0ivzbcg"/><path class="x22kdubov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:white-paper" {...props}></Icon>
