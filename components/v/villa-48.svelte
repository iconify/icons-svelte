<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kixdt2b5z.css';
import '../../css/q/qwnitvbfh.css';
import '../../css/r/r2evrhb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kixdt2b5z"/><path class="qwnitvbfh"/><path class="r2evrhb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:villa-48" {...props}></Icon>
