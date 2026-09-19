<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmr0a4q_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lmr0a4q_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:square-xmark" {...props}></Icon>
