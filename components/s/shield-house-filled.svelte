<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqeizzbud.css';
import '../../css/u/umfrdlbme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pqeizzbud"/><path class="umfrdlbme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:shield-house-filled" {...props}></Icon>
