<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckj36vb5o.css';
import '../../css/t/tmqztg9xx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ckj36vb5o"/><path class="tmqztg9xx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scroll-48" {...props}></Icon>
