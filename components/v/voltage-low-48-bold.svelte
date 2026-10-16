<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9leiv1ic.css';
import '../../css/n/ndcyp2oof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g9leiv1ic"/><path class="ndcyp2oof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:voltage-low-48-bold" {...props}></Icon>
