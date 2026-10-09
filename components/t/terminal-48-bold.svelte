<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/woaiz3jcj.css';
import '../../css/t/t2uupdbom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="woaiz3jcj"/><path class="t2uupdbom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:terminal-48-bold" {...props}></Icon>
