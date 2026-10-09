<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsx9bkbtz.css';
import '../../css/k/kfvih2rid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jsx9bkbtz"/><path class="kfvih2rid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:zoom-out-20" {...props}></Icon>
