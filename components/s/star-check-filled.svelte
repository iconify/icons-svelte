<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqd7f1bqb.css';
import '../../css/e/eatsjcb_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mqd7f1bqb"/><path class="eatsjcb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:star-check-filled" {...props}></Icon>
