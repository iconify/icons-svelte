<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o787acb6i.css';
import '../../css/u/u-8yf-b3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o787acb6i"/><path class="u-8yf-b3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:whistle-48-bold" {...props}></Icon>
