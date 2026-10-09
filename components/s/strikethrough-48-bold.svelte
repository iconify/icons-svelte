<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwnfq9ybn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cwnfq9ybn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:strikethrough-48-bold" {...props}></Icon>
