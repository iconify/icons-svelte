<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn6as_b4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qn6as_b4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:skip-back-48-bold" {...props}></Icon>
