<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0o6xb60y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q0o6xb60y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:status-closed" {...props}></Icon>
